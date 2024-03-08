# Streamlit Indian Startup Funding Data Visualization
Welcome to the Streamlit Indian Startup Funding Data Visualization project! This project aims to provide comprehensive visualizations and analysis of the Indian startup funding dataset using Pandas, Plotly, and Streamlit. It offers interactive plots and informative tooltips to explore various aspects of startup investments and investors.


<H1>Table of Contents</H1>
<ul>
  <li>Project Overview</li>
  <li>Installation</li>
  <li>Dataset</li>
  <li>Website Structure</li>
  <ul><li>Section 1: Overall Analysis</li>
    <li>Section 2: Startup Analysis</li>
    <li>Section 3: Investor Analysis</li>
  </ul>
  <li>How to Use</li>
  <li>Contributing</li>
  <li>License</li>
  <li>Contact</li>
</ul>

<h1>Project Overview</h1>
The Streamlit Indian Startup Funding Data Visualization project is a personal project developed to analyze and visualize the Indian startup funding dataset. It provides a web-based interface built with Streamlit, allowing users to explore the dataset and gain insights through interactive plots and metrics. The project utilizes Pandas and Plotly libraries for data manipulation and visualization, respectively.

The main objectives of this project are:

<ul>
<li>1.Perform an overall analysis of the startup funding ecosystem in India.</li>
<li>2.Enable analysis of individual startups based on user selection.</li>
<li>3.Provide insights into individual investors based on user selection.</li>
</ul>

<h1>Installation</h1>
To run the project locally, follow the steps below:
<ul>
  <li>Clone the GitHub repository:</li>
</ul>

import streamlit as st
def main():
    st.title("Copy Paste in streamlit")
    pathinput = st.text_input("Enter your Path:")
    #you can place your path instead
    Path = f'''{pathinput}'''
    st.code(Path, language="python")
    st.markdown("Now you get option to copy")
if __name__ == "__main__":main()
