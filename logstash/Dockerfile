FROM logstash:5

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
COPY plugin/logstash-filter-elapsed-plugin_4.0.1-offline.zip /tmp
RUN logstash-plugin install file:///tmp/logstash-filter-elapsed-plugin_4.0.1-offline.zip
