# ml_flow_orch_with_Prefect
ML_flow orchestration with Prefect
perfect - opensource workflow orchestration tool
easily transform any Python function into a unit of work that can be observed and orchestrated by simply adding a few decorators to the code

## perfect task
@task decorator - 
"""
from prefect import task


@task
def print_message():
    print("Hello, I'm a task")


if __name__ == "__main__":
    print_message()
"""