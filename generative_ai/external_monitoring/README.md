# Observability
This folder consists of starter python code that DataRobot users can use to enable observability for external models. Say for instance, you have a agentic workflow or LLM appliction already running. Using our external observability you can leverage DataRobot to monitor that model with a simple decorator. 



## Monitoring Decorator

The included "monitoring.py" is a python decorator that wraps the [DataRobot Monitoring Agent](https://docs.datarobot.com/en/docs/mlops/deployment/mlops-agent/monitoring-agent/index.html#monitoring-agent) using it to report the prompt and response of our generative application. You can lift that file at drop it directly in your workflow. 

