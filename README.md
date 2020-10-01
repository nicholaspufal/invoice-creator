# Invoice Creator

A simple invoice creation tool to help you bill your tech clients.

![Sample Invoice](https://user-images.githubusercontent.com/680151/47966699-92c76200-e03c-11e8-8b22-f4fa3e63ef75.png)

## Set up

1. Install dependencies with `bundle install`
2. Edit `config.yml` according to your preferences - define your rate, date format,
currency format, invoice number mask and what should be part of the to/from/extra
fields in the invoice.
3. You might want to `chmod +x bin/invoice_creator`. Optionally just run it with `ruby`.
4. Run `./bin/invoice_creator help create` for a more comprehensive explanation on
how to use it

## Usage example

Let's say we want to create an invoice that represents 168 billable hours and has
invoice number set to 10:

```bash
./bin/invoice_creator create 168 --number 10
```
