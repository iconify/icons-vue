<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="n7ymipb_g"/><path class="jkthf1l_a"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tkn-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jkthf1l_a {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.25 5.528L13.75 4v4h4.5v3h-4.5v4.695c0 1.472 2.578 1.64 3.5 1.152l.828 2.544c-2.031 1.208-7.828.92-7.828-3.671zM7.289 11.6c-.851 0-1.539-.856-1.539-1.912s.695-1.904 1.547-1.904c.859 0 1.546.848 1.546 1.904c0 1.048-.687 1.903-1.546 1.903z");
}

.n7ymipb_g {
  fill: var(--svg-color--24dd7b, #24dd7b);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
