## Crawls Data Built With Ruby
> This is a simple web scrapper that   basically crawls a website and retrives  specific data from the site. 

#### For this particular project, we will be scrapping https://coinmarketcap.com/ which is a website that provides information on different cryptocurrencies and we will be retrieving the following data:
- Name of the cyrptocurrency
- Market Capitalization
- Price
- Volume
- Circulating supply
- Change(%)

![Screenshot](https://github.com/hoangmanhkhiem/Crawls-Price-Crypto/blob/main/assests/test2.png)
 
### Built With
- Ruby
- Nokogiri gem
- Open-uri gem

### Prerequisites

Since all the code is written using ruby `Ruby Runtime >= 1.9` ruby is required to interpret the code. if you don't have ruby runtime installed on your computer follow the instruction for your specific operating system on the [official installation guide](https://www.ruby-lang.org/en/documentation/installation/)

### Getting started

To get a local copy up and running follow these simple example steps.

- Clone or download this repository to your local workstation.
- enter the directory of the cloned project
- run bin/controller.rb to execute the scrapper script and print out the data retrieved to the console.

### Testing

For testing RSpec is used. To run test run the following command line.

`rspec`

## Author

👤 **Hoang Manh Khiem**

## Show your support

Give a ⭐️ if you like this project!

## 📝 License

This project is [MIT](lic.url) licensed.

