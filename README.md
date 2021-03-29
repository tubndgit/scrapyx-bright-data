# scrapyx-bright-data

[Bright Data](https://brightdata.com/?affiliate=ref_5c7c6f828fcb5320de302843) middleware for [Scrapy](http://scrapy.org/)

Required
--------

    python version >= 2.7


Install
--------

Checkout the source and run

    python setup.py install

Or

    pip install scrapyx-bright-data


settings.py
-----------

    # Activate the middleware
    BRIGHTDATA_ENABLED = True
    
    # The Bright Data URL
    BRIGHTDATA_URL = 'http://127.0.0.1:24000'

    DOWNLOADER_MIDDLEWARES = {
        'scrapyx_bright_data.BrightDataProxyMiddleware': 610,
    }
