
Together AI plugin allowing you to use them as your LLM

## Configuration

To use you've got to override the default slots used for chatting with an LLM as follows in your configuration object.

```json
{
  "magic": {
    "together_ai": {
      "token": "ta_TOKEN_HERE",
      "model": "deepseek-r1/DeepSeek-R1-OR-MODEL-YOU-WISH-TO-RUN",
      "max_tokens": 128000_MAX_TOKEMS_ABOVE_MODEL_CAN_HANDLE
    },
  }
}
```
