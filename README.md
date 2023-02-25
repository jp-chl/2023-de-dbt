Welcome to your new dbt project!

### Using the starter project

Try running the following commands:
- dbt run
- dbt test


### Resources:
- Learn more about dbt [in the docs](https://docs.getdbt.com/docs/introduction)
- Check out [Discourse](https://discourse.getdbt.com/) for commonly asked questions and answers
- Join the [dbt community](http://community.getbdt.com/) to learn from other analytics engineers
- Find [dbt events](https://events.getdbt.com) near you
- Check out [the blog](https://blog.getdbt.com/) for the latest news on dbt's development and best practices


### dbt setup

- ```dbt run``` does not consider seed
- ```dbt build``` does

- ```dbt build --select fact_trips```: runs only fact_trips
- ```dbt build --select +fact_trips```: all that fact_trips needs
- ```dbt run --var 'is_test_run: false'``` updates all without limit clause