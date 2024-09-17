# Module-12-Challenge

## Part 1: Database and Jupyter Notebook Set Up

- This part is pretty straightforward. I was able to import the data from the provided JSON file 'establishments.json' into a Mongo database and complete the set up for manipulating data in the following parts.

- Below is the command I used to import the data and it is saved in the markdown cell in the beginning of the `NoSQL_setup_starter.ipynb`.

    ```shell
    mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json
    ```

## Part 2: Update the Database

- In this part, I added several code cells to count the documents in the `establishments` collection both before and after inserting a new document and deleting existing ones, in order to track the results.

- The code to set non 1-5 Rating Values to null was provided in the starter file, and I applied it before updating the data type from string to integer for field "RatingValue".

## Part 3: Exploratory Analysis

- I was able to find the answers for most of the questions in this part with what I learned in the class and the provided hints in the starter file.

- The most challenging question for me was question 3, which required us to find the establishments that are nearest to the "Penang Flavours" restaurant and were within 0.01 degree on either side of the latitude and longitude. I was able to solve this problem eventually by consulting ChatGPT.

## Resources

Resources that I referred to for completing this homework:

<https://chatgpt.com/>