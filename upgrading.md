---

copyright:
  years: 2015, 2020
lastupdated: "2020-02-10"

subcollection: discovery

---

{:shortdesc: .shortdesc}
{:external: target="_blank" .external}
{:tip: .tip}
{:note: .note}
{:pre: .pre}
{:important: .important}
{:deprecated: .deprecated}
{:codeblock: .codeblock}
{:screen: .screen}
{:download: .download}
{:hide-dashboard: .hide-dashboard}
{:apikey: data-credential-placeholder='apikey'} 
{:url: data-credential-placeholder='url'}
{:curl: .ph data-hd-programlang='curl'}
{:javascript: .ph data-hd-programlang='javascript'}
{:java: .ph data-hd-programlang='java'}
{:python: .ph data-hd-programlang='python'}
{:ruby: .ph data-hd-programlang='ruby'}
{:swift: .ph data-hd-programlang='swift'}
{:go: .ph data-hd-programlang='go'}

# Upgrading your plan
{: #upgrading-your-plan}

{{site.data.keyword.discoveryfull}} offers three plans that provide different levels of resources and capabilities to suit your needs.
{: shortdesc}

See [{{site.data.keyword.discoveryshort}} pricing plans](/docs/discovery?topic=discovery-discovery-pricing-plans) and [{{site.data.keyword.discoveryshort}} catalog](https://cloud.ibm.com/catalog/services/discovery){: external} for details.

## Upgrading your service
{: #service}

To resize your plan from Lite to Advanced:

1. From the [resource list](https://{DomainName}/resources/){: external}, click on your {{site.data.keyword.discoveryshort}} instance to go to the {{site.data.keyword.discoveryshort}} dashboard page.
1. From the **Manage** page of {{site.data.keyword.discoveryshort}}, click **Upgrade** to choose the Advanced plan. Follow the steps on the **Plan** page to complete your upgrade.
1. Return to the **Manage** page and click **Launch Watson Discovery** to open the {{site.data.keyword.discoveryshort}} tooling.
   - If you never created an environment for your Lite plan before the upgrade to Advanced, click the ![Cog](images/icon_settings.png) icon, and choose **Create environment**. Choose the options for the Advanced plan that fit your needs.  (`X-Small`, `Small`, `Medium-Small`, `Medium`, `Medium-Large`, `Large`, `X-Large`, `XX-Large`).
   - If you created an environment for your Lite plan before the upgrade to Advanced, your new Advanced plan environment is set to `Small` by default.

## Switching from one Advanced tier to another
{: #switchadvanced} 

If you already have an Advanced plan, and would like to upgrade it to a larger plan size, you can do so using the [API](https://{DomainName}/apidocs/discovery#update-an-environment){: external}. 

For detailed information on Advanced plan storage limits and pricing, see [Advanced pricing plans](/docs/discovery?topic=discovery-discovery-pricing-plans#advanced).

Available Advanced plan sizes are: 

Plan size | Label  
--------- | ------ 
X-Small | XS 
Small | S 
Medium-Small | MS 
Medium | M 
Medium-Large | ML 
Large | L
X-Large | XL 
XX-Large | XXL 

- Querying and indexing can proceed during upgrading. The time required for upgrading depends on a number of factors. You can poll your environment, using the API, while the upgrade completes.
- Moving from one level of Advanced to another does not require the creation of new instances.
- After the upgrade is complete, you are billed at the new plan rate.
- If you later find that you need a smaller plan size, set up the appropriate plan size, migrate your data, and cancel the larger plan.

## Upgrading to a Premium plan
{: #premium}

If you are interested in a Premium plan, contact [Sales](https://ibm.biz/contact-wdc-premium).  
