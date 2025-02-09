<!-- Learn how to maintain this file at https://github.com/WordPress/gutenberg/tree/HEAD/packages#maintaining-changelogs. -->

## Unreleased

## 0.8.0 (2024-03-21)

### Enhancement

- Two new operators have been added: `isAll` and `isNotAll`. These are meant to represent `AND` operations. For example, `Category is all: Book, Review, Science Fiction` would represent all items that have all three categories selected.
- DataViews now supports multi-selection. A new set of filter operators has been introduced: `is`, `isNot`, `isAny`, `isNone`. Single-selection operators are `is` and `isNot`, and multi-selection operators are `isAny` and `isNone`. If no operators are declared for a filter, it will support multi-selection. Additionally, the old filter operators `in` and `notIn` operators have been deprecated and will work as `is` and `isNot` respectively. Please, migrate to the new operators as they'll be removed soon.

## 0.7.0 (2024-03-06)

## 0.6.0 (2024-02-21)

## 0.5.0 (2024-02-09)

## 0.4.0 (2024-01-24)

## 0.3.0 (2024-01-10)

## 0.2.0 (2023-12-13)
