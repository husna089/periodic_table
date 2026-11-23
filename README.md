# Periodic Table Database

This project is part of the freeCodeCamp Relational Database certification.

## Files

- `element.sh`: Bash program to search for chemical elements.
- `periodic_table.sql`: PostgreSQL database backup.

## Usage

Run the script with an atomic number, symbol, or element name:

```bash
./element.sh 1
./element.sh H
./element.sh Hydrogen
```

If no argument is provided, the script asks for an element argument.

If an element does not exist, the script displays a not-found message.

## Database

The database contains chemical element information, including atomic number, symbol, name, atomic mass, melting point, boiling point, and element type.
