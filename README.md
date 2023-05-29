# Smash Bros N64 Community Website


Welcome to the Smash Bros N64 Latam Community Website repository. This project serves as a central platform for players to access information, share content, and connect with each other.


## Getting Started


To run this project locally, make sure you have the following dependencies installed:


- [Ruby](https://www.ruby-lang.org/) version 3.2.2
- [Rails](https://rubyonrails.org/) version 7.0.5
- [PostgreSQL](https://www.postgresql.org/) version 12 or higher


For detailed installation instructions, please refer to the following resources:


- [Ruby Installation Guide](https://gorails.com/setup)
- [Rails Installation Guide](https://gorails.com/setup)


## Setup


Follow these steps to set up the project:


1. Clone the repository: `git clone https://github.com/smash64-latam/ror-site.git`
2. Install Ruby dependencies: `bundle install`
3. Set up the PostgreSQL database:
  - Ensure PostgreSQL is running on your system.
  - Update the `config/database.yml` file with your PostgreSQL configuration.
  - Run the following commands:
    ```
    rails db:create
    rails db:migrate
    ```
4. Start the Rails server: `rails server`


## Contributing


We welcome contributions to the Smash Bros N64 Community Website project. If you would like to contribute, please follow these steps:


1. Create a new branch from the `develop` branch: `git checkout -b feature/your-feature-name`
2. Make your changes and commit them.
3. Push your changes to your forked repository: `git push origin feature/your-feature-name`
4. Open a pull request on the main repository.


Please ensure that your code follows the project's coding guidelines and that it is thoroughly tested.


## Additional Information


For additional information and documentation, please refer to the following resources:


- [Official Ruby Documentation](https://www.ruby-lang.org/en/documentation/)
- [Official Rails Guides](https://guides.rubyonrails.org/)
- [PostgreSQL Documentation](https://www.postgresql.org/docs/)


## License


This project is licensed under the [MIT License](LICENSE).