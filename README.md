# GoodData Cloud Analytics as a Code

Here we demonstrate a simple work with a [GoodData Cloud](https://www.gooddata.com/docs/cloud/) workspace definition.

Once a user pushes a change to the `main` brach, action pushes that back to GoodData Cloud where it originally came from.

You can think of this project as a basis for a collaboration platform where users can introduce various capabilities using branch functionality.

[![](https://mermaid.ink/img/pako:eNpVUsluwjAQ_ZXRnEANCAhkO1QCInEBtWoPVatcprEhEYkncpxSCvx7s1BUfLLfm7fI9gljFhID3GZ8iBPSBtYvkYJ6zXsrZhGSIVhmXAno4DfW-7KgWPZhMHg8r6QBIbepSk3K6gyL3ppjyuB9vllDaVjTTl6V8ABfZRMHJASrfocuWpvnqkzAMGhZcJnWsuMZlqdVapLq8x_YSQ41fB9w6Yhl6_WkIOY8T80Zwj8Lipt617HwGnnffB4ptHCnU4HBlrJSWphLnVNzxlOjjDBj3kcY1LuElAg1HVSEVseZROayIwXpeixSl9qwIPXBnGNgdFVbaq52yS2gKgQZGaa005TfUKoMvx5VfNNIJaRecqUMBt6k9cTghN8YTOyh77tjz3P9qe_4s5lj4RGDsT0a2u7Un04cx7dnU8e7WPjT1hgNPXdmoRTNhW66x2__wOUXPCynWQ?type=png)](https://mermaid.live/edit#pako:eNpVUsluwjAQ_ZXRnEANCAhkO1QCInEBtWoPVatcprEhEYkncpxSCvx7s1BUfLLfm7fI9gljFhID3GZ8iBPSBtYvkYJ6zXsrZhGSIVhmXAno4DfW-7KgWPZhMHg8r6QBIbepSk3K6gyL3ppjyuB9vllDaVjTTl6V8ABfZRMHJASrfocuWpvnqkzAMGhZcJnWsuMZlqdVapLq8x_YSQ41fB9w6Yhl6_WkIOY8T80Zwj8Lipt617HwGnnffB4ptHCnU4HBlrJSWphLnVNzxlOjjDBj3kcY1LuElAg1HVSEVseZROayIwXpeixSl9qwIPXBnGNgdFVbaq52yS2gKgQZGaa005TfUKoMvx5VfNNIJaRecqUMBt6k9cTghN8YTOyh77tjz3P9qe_4s5lj4RGDsT0a2u7Un04cx7dnU8e7WPjT1hgNPXdmoRTNhW66x2__wOUXPCynWQ)

## Details

- Connection details are defined in [`gooddata.yaml`](./gooddata.yaml) file
- [Command-line Interface](https://www.gooddata.com/docs/cloud/api-and-sdk/vs-code-extension/cli/) used to push definition to GoodData: `@gooddata/code-cli`
- Definitions are stored in the [`analytics`](./analytics/) folder