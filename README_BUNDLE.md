# {book_titles[]}

_{book_titles[]}_ are textbooks published by [OpenStax](https://openstax.org/), a non profit organization that is part of [Rice University](https://www.rice.edu/).

These books can be viewed online and as a pdf.
_{book_title}_ [online](https://openstax.org/details/books/{book_slug}) [pdf](https://assets.openstax.org/oscms-prodcms/media/documents/###.pdf).
_{book_title}_ [online](https://openstax.org/details/books/{book_slug}) [pdf](https://assets.openstax.org/oscms-prodcms/media/documents/###.pdf).
{{ repeat for remaing books }}

## Sumary of {book_title}
{{ summary section from: https://openstax.org/details/books/{book_slug} }}

## Sumary of {book_title}
{{ summary section from: https://openstax.org/details/books/{book_slug} }}

{{ repeat for remaining books }}

## License
These books are available under the [{license}](https://github.com/openstax/content-synchronizer/blob/main/licenses/{license}) license.

## Support
If you would like to support the creation of free textbooks for students, your [donations are welcome](https://riceconnect.rice.edu/donation/support-openstax-banner).

## Senior Contributing Authors for Books in {repo_name}
{{ senior contributing authors can be found in CNXML, followed with {book_title[s]} that contributed to }}

## Contributing Authors for Books in {repo_name} (optional)
{{ contributing authors section can be found in CNXML, followed with {book_title[s]} that contributed to }}
