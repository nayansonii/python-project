import streamlit as st

# Streamlit app
st.title("User Registration")

# Input form
first_name = st.text_input("First Name")
last_name = st.text_input("Last Name")
vechile_number = st.text_input("Vechile Number")
bankaccount_number = st.text_input("Bank Account Number")

# Save data on submission
if st.button("Submit"):
    # Store data as a string
    user_data = f"{first_name} {last_name},{vechile_number},{bankaccount_number}\n"
    

    # Save to a text file
    with open("user_data_base.txt", "a") as text_file:  # 'a' mode appends to the file
        text_file.write(user_data)

    st.success("Data saved in the data base")
    st.write("\n")
    st.button("you can now add funds")
