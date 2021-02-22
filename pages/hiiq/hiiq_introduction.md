---
title: Introduction
sidebar: hiiq_sidebar
permalink: hiiq_introduction.html
folder: hiiq
---

## Overview

HIIQ (pronounced High IQ) is Happy Playgrounds Customer Quoting system. The acronymn HIIQ stands for Happy Information Inquiry Quote. HIIQ is written in Ruby on Rails and is hosted on the Heroku platform. HIIQ utilizes a postgres database to store information.

The goal of HIIQ is to improve the turnaround time between a customer inquiry and Happy's response with a formal quote. It all starts with Customer. You have to have a Customer in HIIQ before you can proceed in creating a quote. And no supply chain would not be complete without Vendors, so HIIQ allows you to assign vendors to the quote line items. Although you don't need an vendor loaded in HIIQ to create a quote. But if your Vendor is approved and active in HIIQ you can create a purchase order for the products the vendor provides on your quote. Although Happy does not currently stock inventory HIIQ does support loading Vendor products and currently has 2021 pricing for Wabash Valley and the majority of Playworld products. Approximately 150,000 part numbers are loaded.


We will be getting into more details related to quotes, customers, vendors and products in the appropriate sections. 

Note: Happy Playgrounds will be refered to as Happy in the remainder of this documentation.


{% include links.html %}
