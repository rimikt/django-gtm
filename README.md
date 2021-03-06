Google Tag Manager App
-----
Simple app that intends to simplify GTM configuration and allows to add named
settings for different containers.

Google Tag Manager https://tagmanager.google.com


Usage
===

1. Do migrations
2. Open GTM settings in the admin page
3. Set value for Default GTM Settings
4. Add named GTM Settings
5. Use default or named GTM settings whenever you need in your templates.

Examples
===

1. Custom code

    ```
    {% gtm "GTM-FNHEHD" %}
    {% gtm_head "GTM-FNHEHD" %}
    {% gtm_body "GTM-FNHEHD" %}
    ```

2. Default value

    ```
    {% gtm %}
    {% gtm_head %}
    {% gtm_body %}
    ```

3. Named settigns

    ```
    {% gtm name="name1" %}
    {% gtm_head name="name1" %}
    {% gtm_body name="name1" %}
    ```
