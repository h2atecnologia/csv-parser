# Snapshot report for `test/headers.test.js`

The actual snapshot is saved in `headers.test.js.snap`.

Generated by [AVA](https://ava.li).

## custom escape character

> first row

    {
      a: '1',
      b: 'some "escaped" value',
      c: '2',
    }

> second row

    {
      a: '3',
      b: '""',
      c: '4',
    }

> third row

    {
      a: '5',
      b: '6',
      c: '7',
    }

## headers option

> Snapshot 1

    [
      {
        a: '1',
        b: '2',
        c: '3',
      },
      {
        a: '4',
        b: '5',
        c: '6',
      },
      {
        a: '7',
        b: '8',
        c: '9',
      },
    ]

## headers: false

> Snapshot 1

    [
      {
        0: 'a',
        1: 'b',
        2: 'c',
      },
      {
        0: '1',
        1: '2',
        2: '3',
      },
      {
        0: '4',
        1: '5',
        2: '6',
      },
      {
        0: '7',
        1: '8',
        2: '9',
        3: '10',
      },
    ]
