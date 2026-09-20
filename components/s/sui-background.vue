<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="wg_4enk7f"/><path class="v9eycccdz"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sui-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.v9eycccdz {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.67 10.674a4.84 4.84 0 0 1 1.021 2.983a4.86 4.86 0 0 1-1.05 3.021l-.056.07l-.014-.094a5 5 0 0 0-.047-.23c-.33-1.473-1.393-2.739-3.152-3.764c-1.186-.687-1.868-1.515-2.047-2.457a3.6 3.6 0 0 1 .14-1.75c.135-.44.343-.854.617-1.223l.687-.857a.295.295 0 0 1 .461 0zm1.082-.856L12.17 4.082a.215.215 0 0 0-.263-.06a.2.2 0 0 0-.075.06l-4.584 5.74l-.014.014a6.3 6.3 0 0 0-1.35 3.915C5.883 17.201 8.62 20 12 20s6.117-2.8 6.117-6.249a6.3 6.3 0 0 0-1.35-3.915zm-8.408.837l.41-.513l.013.094l.033.226c.268 1.426 1.214 2.612 2.8 3.53c1.379.804 2.178 1.726 2.409 2.738c.094.423.113.837.07 1.2v.023l-.018.01c-.64.32-1.346.485-2.061.484c-2.588 0-4.691-2.145-4.691-4.79a4.83 4.83 0 0 1 1.035-3.002");
}

.wg_4enk7f {
  fill: var(--svg-color--4ba2ff, #4ba2ff);
  d: path("M24 0H0v24h24z");
}

</style>
