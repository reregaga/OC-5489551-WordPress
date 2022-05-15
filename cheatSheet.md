Course objectives:
- upload WordPress to a host
- take charge of the WordPress administration
- configure the theme and plugins of a WordPress site
- customize the content and design of a WordPress site
- optimize the configuration of a WordPress site.

# Part 1 - Discover WordPress and deploy your site quickly
## Discover WordPress
WordPress (anymore, anyway) is not a blogging platform; today it is a platform used to create all types of sites, from simple **blog**s to **e-commerce site**s, including **intranet solution**s, complex web applications, and even **mobile application**s!

WordPress is **CMS**, tool that offers an interface for creating and managing the content of your website, rather than manually coding everything.

https://wordpress.org

## Learn how a website works
#TODO:

## Choose your host and put your WordPress site online
### Alternative: Build Your Site Locally
If you don't want or don't want to go through hosting, you can still work on your site! The only limitation is that it will only be accessible from your computer. This is called working "locally". There are various solutions for installing your site locally. The most famous is installing **MAMP** or **WAMP**, but now there is an easier and faster solution. This is Local by Flywheel, a free software available for Mac and PC that makes it easy to build a WordPress site locally using Docker containers.

- To get started, go to https://local.getflywheel.com , click Download and enter the requested information.
- After downloading the software, open it and click "Start" to start installing all components.
- Once the software is installed, click the plus icon, Add New Site, and enter the requested information (select PHP version 7).
- Once the site is created, it will appear in the left column. Click on it to display the access. You can start working!

# Part 2 - Take control of the administration of your WordPress site
## Log in to the WordPress dashboard and create your first post
Typically, to connect to the WordPress site administration interface, you need to go to the URL `monsite.com/wp-login.php`, which is the default login URL. You can also go to the toolbar URL `monsite.com/wp-admin` which will automatically redirect you to it. You can then enter your login credentials.

### WordPress Login URL
Since the **default login URL is the same for all WordPress sites**, it is very easy for **hackers to try to connect to sites** by "brute force" (i.e. by checking many login/password associations).

>That's why:
>- it is absolutely essential to avoid choosing too simple IDs and passwords (the "admin" login ID should be avoided!);
>- It is recommended that you change the default login URL to a hard-to-find custom URL; we will see how to do this in the next chapter.

WordPress offers two types of content by default: **posts** and **pages**. The difference between the two lies in the timing of the publication and the way it is accessed.
- **Post** is usually current, outdated content that acquires the most value at the time of publication. It can usually be accessed through a page with a list of posts sorted in reverse order (latest posts published first), rather than through a special link in the navigation menu. In short, this is what is called a blog!
- **Page** is static content, usually undated and of constant value over time. It is typically used to represent the company (About Us page), service (Our Services page), contact information and features (Contact page), and is usually accessed via menu navigation (in the header or footer)).

WordPress also allows you to create custom content types, also called **custom post types**. So the "Products" content type is created when you install WooCommerce, the #1 eCommerce extension for WordPress.

### Create post
Just click on the "**Document**" tab and add a category to your post in the "**Categories**" block. To do this, click "**Add a new category**", enter the name of the desired category (we will put "**Miscellaneous**", later you will understand why) and type "**Enter**".

>WordPress offers two ways to sort articles by default:
>- **Categories** that are hierarchical (you can create subcategories of ) and need to be carefully chosen to properly reflect the blog's topics and optimize its natural links. We usually assign only one category (or subcategory) to each article and try not to multiply the total number of suggested categories. For example, a Banana Chocolate Cake recipe article would have a Cakes category, a Desserts subcategory, and a Recipes subcategory;
>- **Tags** that do not have a hierarchy and can be assigned in bulk to each article. Their goal is to identify important topics covered in the article and recurring in the blog. If we take our Banana Chocolate Cake recipe as an example, we can, for example, give it the tags "banana", "chocolate", and "evil pleasure".

Additonal info about categories: https://www.siteground.com/tutorials/wordpress/use-categories/

## Set up your WordPress site options
#TODO:

## Set up a personalized homepage and create your navigation menu
#TODO:

## Customize the appearance of the site with the customizer
#TODO:

# Part 3 - Choose, install and configure the WordPress components suitable for your project
## Define the type of site you want to create
### Determine site goals
Before you start creating a site, you need to clearly define the goals of the latter. Indeed, to take extreme examples, we will not create the same type of sites if our goal is to sell products online (e-commerce site) or share tips and good plans (blog).

In our case, our goal is to find clients for our WordPress site building activity! Thus, this is a site that will be aimed at establishing business contacts. That means:
- that it is visually appealing;
- that it convinces us of our professionalism through recommendations and/or customer reviews;
- that visitors can easily leave a message or even request a quote via a contact form;
- that visitors are encouraged to subscribe to the newsletter so that we can keep in touch after they leave the site (optional).

>**Business contacts are valuable**, and visitors have little time and attention. It is for this reason that many sites offer, sometimes somewhat aggressively, to **subscribe to a newsletter**. This **allows you to keep in touch with the visitor in order to later turn the contact into a buyer**!

### Think about SEO from the very beginning
Natural link optimization is often referred to as SEO for "**Search Engine Optimization**".

In a word, these are **all tricks aimed at raising your site in the results of search engines such as Google**. This is very important as it usually results in the **vast majority of visits to your site** (unless you have an advertising budget or inbound links from high traffic sites)!

Define the search terms you want to position yourself on. In our case, we want to rank well for keywords like "web agency". However, this is too general a term that many agencies are already guided by. Therefore, we will try to refine the search expression by adding the location: "bordeaux web agency". By doing a Google web agency research, we can understand that there is still a lot of competition for this search term and it can be very difficult to get back to the first page. Therefore, we can further clarify the specialty, for example, “Wordpress agency in Bordeaux”. There are still a few people, but the first page seems much more accessible! To **select the right search phrases to position yourself** with, you can use tools like [Neil Patel's Ubersuggest](https://neilpatel.com/ubersuggest/) to compare competition and traffic potential between different search phrases.

Goal: to **position yourself on expressions where the competition is as low as possible, but with the maximum potential for traffic**!

>However, this type of tool has its limitations, and sometimes it's better to rely on common sense and Google search results rather than the statistics they offer, especially search terms with little research and for which the generated statistics will be less accurate.

It's very important to define the **primary search expression** we want to position ourselves on, but we also need to define **secondary search expressions**, which can be:
- or variations of the main expression (for example: "WordPress Bordeaux freelance");
- or expressions aimed at additional actions (for example: "Bordeaux SEO agency" or "Bordeaux logo creation").

Once a tree structure (**sitemap**) has been defined, it is a good idea to define the structure of its pages using **wireframes**, that is, very simple diagrams that represent different areas of the page. This can be done simply with pencil and paper, or with dedicated tools like https://cacoo.com or https://wireframe.cc.

## Choose your theme and your page builder
As we saw earlier, one of the strengths of WordPress is that it has thousands of components that allow you to run different types of projects. Therefore, the first thing to do is to select the components that are suitable for our project.

A theme is perhaps the most important component of your WordPress site. It is he who will determine the appearance of your site, design customization options and compatibility with certain functions (e-commerce, etc.).

There are currently two page builders that stand out:
- **Beaver Builder**, more 'developer' oriented, with a free version rather poor in terms of components.
- **Elementor**, which is more focused on "designers" and has a rich library of components, even in the free version. As you have already figured out, this is the one we will be using here.
- **Divi** and **WP Bakery Page Builder** are other popular page builders. At the time of this writing, these builders were heavy, the generated code was not clean, and the user interface was less flexible.
- There are dozens of other very good page builders, such as **Site Origin Page Builder** (free, lightweight, but less intuitive), **Brix** (super-fast, generating very clean code, but with a small community), etc. They may turn out to be more or less relevant depending on the project.

### Learn how to choose your WordPress theme wisely
Depending on the project, it may be preferable to go with one or the other of these types of themes, but in any case, there are some essential aspects to check before you start.

- The **last update date**. If a theme has not been updated for more than 6 months, it is worrying. It may be abandoned by its developer, and you may encounter incompatibilities when updating WordPress or your plugins (WooCommerce…) in the future.
- Notes and **comments**. It's obvious, but almost all theme libraries offer rating and comment systems. Quickly explore these to verify that users do not encounter any particular difficulties!
- **Notoriety**. The more a theme is used, the more likely it is to have qualities, to be regularly maintained, etc. But beware, themes to avoid (overloaded with bling-bling options, etc.) are often very popular too!
- The **loading speed**. A theme generating pages that are too heavy to load will penalize the experience of your visitors and your SEO. More and more themes now offer the ability to disable unused features to make pages load faster.
- The **multilingual** aspect. There's nothing worse than starting to work on a theme and then finding out that it's not meant to be translated.
- The **support**. The existence of good documentation and the responsiveness of the support are very important aspects when facing a difficulty with a theme. Check if there is a well-made documentation and support area, and if the developers respond quickly or not!
- **Source**. Avoid downloading a theme from an unknown site found randomly on the web. Choose themes available on the official WordPress.org library, or on reference shops or marketplaces (Themeforest, Elegant Themes, etc.). The "nulled" themes (initially premium, but offered for free on "pirate" sites) are to be avoided at all costs, they are full of malware (malicious software) and will jeopardize the security of your site!
- **Design quality, flexibility and functionality**. It seems obvious, but check that the design is of quality. Favor clean and minimalist designs over flashy designs that will be more difficult to customize, and may look a lot worse as soon as you start adding your own content. Make sure the theme has enough customization options so you don't have to go through custom CSS if you don't know CSS.
- Finally, check its **compatibility with the plugins you plan to use** (WooCommerce for e-commerce, BuddyPress for collaborative, etc.).

We therefore choose the OceanWP theme which meets all of these criteria and which is also created by a Frenchman.

## Install and configure your WordPress theme
To install a theme, go to **Appearance >> Themes >> Add**.

OceanWP is free and available in the WordPress.org library, so you can just use the search engine to find and install it with one click! Search for “OceanWP” and click on “Install”.

>**Note**: if it was a premium theme or not available on WordPress.org, you would have had to click on “Upload a theme” and select the archive (.zip) of the theme previously downloaded on your workstation. It is also possible to install a theme or a plugin by directly depositing the folder of the latter in the `wp-content/themes` or `wp-content/plugins` directory via FTP.

You can see that a notification has appeared in the WordPress dashboard asking you to install the recommended plugins. Click "**Start Installing Plugins**". You will be redirected to a page with a list of recommended plugins. Select them all by checking the box to the left of Plugins, select Install from the Bulk Actions drop-down menu, and click Apply. The plugins are then automatically installed and activated. The link then prompts you to return to the dashboard home page, click on it to go there.

You can visit your site and see that the design has completely changed.

>OceanWP has a special feature called "Setup Wizard". It allows you to define basic theme settings and **import the entire demo site** in just a few clicks.

## Choose and install relevant WordPress plugins for your project
A WordPress plugin is a WordPress component that allows you to add functionality that is not available in WordPress. There are thousands of plugins that, like themes, may be free or paid, and may or may not be available in the official WordPress.org library.

>**Addons**  
>Some WordPress components have plugins dedicated to them, these are kind of plugins for plugins (or plugins for themes). This is the case, for example, of the Ocean Extra plugin installed previously. There are also a lot of them for Elementor, the page builder we use; just search for “Elementor” in the WordPress.org plugin library to get an idea!

For our example, we will choose:
- "**SEO Press**" (or Yoast SEO) to optimize natural referencing;
- “**Broken Link Checker**” to be alerted in the event of a broken link on our site;
- “**Redirection**” to identify 404 errors and redirect them to existing pages;
- “**ShortPixel**” to optimize the weight of the images;
- “**Duplicate Page**” to easily duplicate a page, an article or any other type of content;
- “**Central color palette**” to centrally define the colors available in the theme and classic WordPress editor color choice palettes.

All of these plugins are available at WordPress.org. So install them directly from **Plugins >> Add**

# Part 4 - Customize the content and design of your WordPress site
## Define the overall design of your site
#TODO:

## Get started with Elementor and design your homepage
https://wordpress.org/plugins/envato-elements/

## Integrate additional features with extensions
### Inserting the form into the page
#### Solution 1: use a shortcode
To insert a feature into an article or a page, the historical and most widespread solution is the use of “shortcodes” (or “codes courts”, in French).

>Important: shortcodes are simple to use codes that can contain variables. They are interpreted dynamically when generating the page to be replaced by the block of functionality with which they are associated.

To get the WP Forms shortcode, click on “**Embed**” at the top. The resulting shortcode should look like: `[wpforms id="437" title="false" description="false"]`.

#TODO:

### Back up your site regularly with Updraft Plus
It's important to back up your site regularly, even if your web host offers automatic backups.  
Indeed, although exceptional, accidents are always possible on servers or datacenters. And it must be understood that in this case you lose absolutely all your work if you do not have remote backups.

Fortunately, free plugins make it easy to back up your site to your machine or to remote locations like Google Drive.

>Be careful, by default, these plugins will save your site on your hosting. This not only takes up space on your hosting but also does not protect you from an incident at your host; it is therefore essential to configure your backups on remote storage spaces!

We will use the “**Updraft Plus**” plugin to upload a backup to our machine and schedule daily automatic backups to Google Drive. Start by installing the plugin in **Plugins >> Add**.

## Integrate advanced features
We have seen previously how to ask search engines not to index the website, which prevents visitors from falling on it during development. This is sometimes not enough, and some customers want the site to be completely inaccessible to the public until launch.

You have two options for doing this:
- use a specialized extension like “Maintenance”, but the options are quite limited;
- use Elementor which allows you to create a completely personalized page.

For this, we will create an Elementor template.

# Part 5 - Finalize and launch your WordPress site
## Optimize SEO and track your site traffic
### In summary
- It is essential to optimize the SEO of your site before launching it.
- Some optimizations are done off-site. Of particular note is the creation of Google Business and Google Search Console profiles, and the creation of inbound links.
- Other optimizations are done directly on the site (on site). Note in particular the optimization of content, markup (h1, h2, h3) and metas (title and description).
- Specialized extensions for SEO, such as SEO Press, Yoast or RakMath, help you optimize SEO “on site” but it is indeed an accompaniment: installing them is unfortunately not enough to optimize the SEO of a site.

## Optimize your site's loading times
Many tools allow you to measure page load time. The best known are **GT Metrix** and **Pingdom**. Here we will use GT Metrix.

A quick and easy way to optimize your page load times is to install a **cache** plugin. This allows pages to be temporarily stored so that they are not completely re-created on each visit and thus delivered to visitors faster.

Caches are of several types:
- OP's cache, which caches files: only cleared if you change the site's files, e.g. via FTP;
- application cache (which is configured through the plugin and caches pages and / or requests to create them);
- and the server cache (which is configurable on the host side and which normally caches all pages (full page cache)).

The most efficient is the server cache, but not all hosts offer it.

I recommend using the **WP Rocket** cache plugin, developed by French WordPress company WP Media! It's very easy to use, extremely efficient, and has a good French-speaking support team. It covers both cache and static resource loading optimization. However, this plugin is paid, so it is not necessarily suitable for all projects.

A good free alternative is the **WP Super Cache** plugin, which is very easy to use and provides good performance. If you're feeling like an expert, you can also take a look at W3 Total Cache, which is also free but offers many options for fine tuning performance.

However, this extension does not cover resource loading optimization, so you can link it to the **Autoptimize** plugin that handles these aspects.

## Checks to do before launching your site
### Protect from hackers
- Wordfence (free plugin), or SecuPress (paid plugin)
- WPS Hide Login (free plugin)

## Connect your domain name and finalize your configurations
Very practical script that allows you to easily modify all the URLs in the database, **Search Replace by Interconnect.it**.  
https://interconnectit.com/search-and-replace-for-wordpress-databases/

It is enough:
- download the script archive, unzip it and rename the folder with a simple name like “Searchreplace”;
- upload it to your server via FTP or your host's file manager;
- go to the URL [mydomain.com]/searchreplace;
- enter the old domain in the left field (for example mysite.olddomain.com) and the new one in the right field (for example newdomain.com).

## Practice building a professional WordPress site
#TODO: