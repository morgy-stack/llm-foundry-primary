# llm-foundry-primary

FOUNDRY Llm

## Built with

- Python (245 files)
- Shell (1 file)

## Getting started

```sh
pip install .
make
docker build -t <image-name> .
```

## Project structure

```
llm-foundry-primary/
    .github/
        ISSUE_TEMPLATE/
            ---bug-report.md
            ---feature-request.md
            ---model-questions.md
        CODEOWNERS
    .pre-commit/
        FILE_HEADER
    assets/
        llm-foundry.png
        radar_blog.png
    llmfoundry/
        algorithms/
            __init__.py
        callbacks/
            __init__.py
            async_eval_callback.py
            curriculum_learning_callback.py
            dataset_swap_callback.py
            env_logging_callback.py
            eval_gauntlet_callback.py
            eval_output_logging_callback.py
            fdiff_callback.py
            hf_checkpointer.py
            kill_loss_spike_callback.py
            log_mbmoe_tok_per_expert_callback.py
            loss_perp_v_len_callback.py
            monolithic_ckpt_callback.py
            resumption_callbacks.py
            run_timeout_callback.py
            scheduled_gc_callback.py
        cli/
            __init__.py
            cli.py
            data_prep_cli.py
            registry_cli.py
        command_utils/
            data_prep/
                __init__.py
                convert_dataset_hf.py
    ...
```
