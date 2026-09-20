<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="uxcas7bac"/><path class="xvw-7acbf"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:valor-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.uxcas7bac {
  fill: var(--svg-color--d8191e, #d8191e);
  d: path("M24 0H0v24h24z");
}

.xvw-7acbf {
  fill: var(--svg-color--fff, #fff);
  d: path("m19.996 4.09l-.997 2.154a.1.1 0 0 1-.03.031a.1.1 0 0 1-.041.011h-2.852a.08.08 0 0 1-.065-.03a.06.06 0 0 1-.003-.064l.003-.005l1.034-2.145a.08.08 0 0 1 .07-.042h2.81a.08.08 0 0 1 .063.03a.06.06 0 0 1 .008.06m-2.377 5.053H8.926l-.932-2.285h5.135c.032 0 .06-.038.07-.069l.926-2.68a.08.08 0 0 0-.008-.072a.08.08 0 0 0-.063-.036H4.076a.07.07 0 0 0-.062.036a.08.08 0 0 0-.009.073l2.959 7.84a.08.08 0 0 0 .071.049h6.692l-1.848 5.212l-1.01-2.87a.075.075 0 0 0-.072-.052l-2.803-.003a.07.07 0 0 0-.062.034a.08.08 0 0 0-.008.075l2.033 5.553a.1.1 0 0 0 .027.037q.02.015.044.015h3.685a.074.074 0 0 0 .071-.05L17.69 9.272c.01-.024.014-.065 0-.086c-.009-.013-.038-.043-.07-.043");
}

</style>
