<%"---"%>
aliases: "<% tp.file.creation_date("YYYYMMDDHHmm") %>"
tags: 
title: <% tp.file.title %>
date: <% tp.file.creation_date("YYYY-MM-DD") %>
created: <% tp.file.creation_date("YYYY-MM-DDTHH:mm") %>
updated: <% tp.file.last_modified_date("YYYY-MM-DDTHH:mm") %>
<%"---"%>
# [[<% tp.file.title %>]]
<% tp.file.cursor() %>