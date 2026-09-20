<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="cv-q9792j"/><path clip-rule="evenodd" class="au-385b1u"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sofi-background" /></template>
<style>
.au-385b1u {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m12 4l-8 8l8 8l8-8zm1.809 3.351l-1.773-1.769l-6.427 6.427L9.52 15.92l3.564-3.56l.676.676l-3.565 3.56l1.796 1.795l6.427-6.427l-3.911-3.91l-3.587 3.582l-.698-.698z");
}

.cv-q9792j {
  fill: var(--svg-color--a950fe, #a950fe);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
