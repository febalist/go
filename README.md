# go

Opens a `claude://` deep link from an https URL, for places that keep only http(s) links (Notion):

    https://febalist.github.io/go/#claude://claude.ai/epitaxy/local_<id>

The link travels after `#`, so it never reaches the server. Other schemes are refused.
