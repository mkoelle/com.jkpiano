# com.jkpiano

John Koelle Piano site

## TODO

- :white_square_button: Infrastructure
    - :white_square_button: Hosting
        - ✔️ dev environment
        - ✔️ production environment
        - :white_square_button: Domain switch
            - Cut domain name servers over from third party to AWS hosted zone
            - Create certificates for https
            - Associate cloudfront with certs and domains
    - ✔️ CI/CD
    - :white_square_button: Analytics - TBD
    - :white_square_button: SEO - TBD
    - :white_square_button: Testing - TBD
    - :white_square_button: Accessibility - TBD
    - :white_square_button: Performance - TBD
- :white_square_button: Site
    - 🔳 Head
        - 🔳 General Metadata
        - 🔳 Page Metadata
    - 🔳 SiteMap
    - :white_square_button: Robot.txt
        - ensure all crawlers are blocked for dev deployment
        - create default robot.txt with links to sitemap
    - :white_square_button: Pages
        - 🔳 Home
            - :white_square_button: Style
                - Hero should reduce padding/margin on mobile view
                - Purchase Section should fix overlap on mobile view
        - :heavy_check_mark: NotFound/404
        - :white_square_button: Blog
            - :white_square_button: Summary page
                - blog listings should have title headers
                - blog listings should display article slugs
                - blog listings should display date authored
                - blog listings should display author
                - blog listings should have read more button
            - :heavy_check_mark: posts:
                - :heavy_check_mark: Purchasing a preowned grand
                - :heavy_check_mark: Consumers guide on how to buy a used piano
        - :heavy_check_mark: General
            - :heavy_check_mark: Biography
            - :heavy_check_mark: Restoration/Process
            - :heavy_check_mark: Restoration/Service
            - :heavy_check_mark: Tuning And Service
            - :heavy_check_mark: Testimonials
        - :white_square_button: Pianos for sale
            - :white_square_button: Summary page
                - listings should show preview image
                - listings should have purchase button link
                - clicking the image or text should also navigate to listing
            - :heavy_check_mark: Listings
        - :no_entry: Contact Us
    - :white_square_button: Header
        - :heavy_check_mark: Navigation
        - :white_square_button: Style
            - :heavy_check_mark: Links should default to white / gold?, does not stand out enough
            - Phone number should be in upper right
            - Nav should collapse in mobile view (hamburger menu)
            - phone number should be sticky in mobile view
    - ✔️ Footer
        - :heavy_check_mark: Navigation
        - :heavy_check_mark: Style

> ### Legend
> :white_square_button: = Incomplete \
> :heavy_check_mark: = Complete \
> ⛔ = Removed

## Tooling

- [astro](https://astro.build/)
    - [Astro-Bootstrap](https://astro-bootstrap.github.io)
    - [@astrojs/mdx](https://docs.astro.build/en/guides/integrations-guide/mdx/)
    - [@astrojs/sitemap](https://docs.astro.build/en/guides/integrations-guide/sitemap/)

## Staging location

- [dev site](https://d3nkr2377cpjg3.cloudfront.net/)