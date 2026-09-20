<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="b6s3gbcxn"/><path class="f9y83nbvx"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:peri-background" /></template>
<style>
.b6s3gbcxn {
  fill: var(--svg-color--14085a, #14085a);
  d: path("M24 0H0v24h24z");
}

.f9y83nbvx {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.998 20a8 8 0 1 0-6.09-2.815l2.35-6.7c.1-.245.465-.735 1.1-.735c.165.005.555.13.825.525a3.2 3.2 0 0 1 1.19-.275c.645 0 2.05.66 1.65 2.225a34 34 0 0 1-1.17 3.48c.25-.035.88-.27 1.35-.925a5.5 5.5 0 0 0 .735-1.33c.07-.13.3-.385.72-.385c.515 0 .73.475.73.885s-1.155 3.55-4.885 3.55l-.13-.01c-.61-.05-1.73-.14-2.14-.35h-.065l-.7 1.455A8 8 0 0 0 11.998 20m-3.32-4.67c-.12.5.205.6.345.65c.03.005.05.015.055.02c.695 0 .92-.51.945-.765c.28-.825.865-2.555.935-2.89c.085-.415.05-.845-.5-.845c-.435 0-.65.36-.71.54c-.305.9-.95 2.81-1.07 3.29");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
