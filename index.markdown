---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home

members: 
  - name: Amazon
    level: premier
    logo: /assets/media/members/amazon-web-services-inc.svg
  - name: Uber
    level: premier
    logo: /assets/media/members/uber-technologies-inc.svg
  - name: Aiven
    level: general
    logo: /assets/media/members/aiven.svg
  - name: Aryn
    level: general
    logo: /assets/media/members/aryninc.svg
  - name: Canonical
    level: general
    logo: /assets/media/members/canonical.svg
  - name: Eliatra
    level: general
    logo: /assets/media/members/eliatra.svg
  - name: Graylog
    level: general
    logo: /assets/media/members/grayloginc.svg
  - name: Portal26
    level: general
    logo: /assets/media/members/portal26.svg
  - name: Netapp
    level: general
    logo: /assets/media/members/netappinc.svg
  - name: Digital Ocean
    level: general
    logo: /assets/media/members/digitalocean.svg
  - name: SAP
    level : premier
    logo: /assets/media/members/sap.svg
  - name: Atlassian
    logo: /assets/media/members/atlassian-inc.svg
    level: general
  - name: DataStax
    logo: /assets/media/members/datastax.svg
    level: general
  - name: DTEX
    logo: /assets/media/members/dtex.png
    level: general
    
    
    
---
<img class="img-fluid " src="/assets/media/ossf-logo.png" width="85%">

The OpenSearch Software Foundation is a project of The Linux Foundation organized to support the OpenSearch open source project.  The mission of the OpenSearch Software Foundation is to provide infrastructure and other resources to enable the long-term sustainability of the OpenSearch open source project and the OpenSearch ecosystem.  You can read the launch announcement [here](https://www.linuxfoundation.org/press/linux-foundation-announces-opensearch-software-foundation-to-foster-open-collaboration-in-search-and-analytics).

A Governing Board (which includes representatives of the OpenSearch Software Foundation’s members and the chair of the technical steering committee of the OpenSearch open source project) oversees the OpenSearch Software Foundation and administers its budget.

The OpenSearch Software Foundation offers three levels of membership:

* Premier Membership ($150,000 annual membership fee, right to appoint a member of the OpenSearch Software Foundation’s Governing Board);
* General Membership (fee ranges from $5,000 to $40,000 depending on consolidated headcount); and
* Associate Membership (no fee) for non-profit organizations.

If your organization is interested in supporting the OpenSearch community, please consider [joining the OpenSearch Foundation which you can do here](https://enrollment.lfx.linuxfoundation.org/?project=opensearch-foundation).

The OpenSearch Software Foundation is not involved in technical oversight of the OpenSearch open source project.  For technical governance of the open source project, please see the project’s technical charter [here](/assets/media/OpenSearch Project Technical Charter Final 9-13-2024.docx.pdf).

#### Premier Members

<div class="container rounded shadow p-3 m-3">
{% assign members = page.members | where: "level", "premier" %}

<div class="container">
<div class="row">
{% for member in members %}
<div class="col-3 rounded p-3 m-3 justify-content-center d-flex">
  <img src="{{ member.logo }}"  alt="{{ member.name }} logo">
</div>
{% endfor %}
</div>
</div>
</div>


#### General Members

<div class="container rounded shadow p-3 m-3">

{% assign members = page.members | where: "level", "general" %}

<div class="container">
<div class="row">
{% for member in members %}
<div class="col-3 rounded p-3 m-3 d-flex justify-content-center">
<img src="{{ member.logo }}" alt="{{ member.name }} logo">
</div>
{% endfor %}
</div>
</div>
</div>


# Contact Us

<script charset="utf-8" type="text/javascript" src="https://js.hsforms.net/forms/embed/v2.js"></script>
<script>
  hbspt.forms.create({
    region: "na1",
    portalId: "8112310",
    formId: "380b9049-2a88-46b8-ac88-e5405e771a1b"
  });
</script>
