<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="m64jxgx-b"/><path class="na4md5b3t"/><path clip-rule="evenodd" class="t3va6px1k"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:plex-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m64jxgx-b {
  fill: var(--svg-color--f08296, #f08296);
  d: path("M24 0H0v24h24z");
}

.na4md5b3t {
  fill: var(--svg-color--fff, #fff);
  d: path("M11 12.499v-3.5h1c1.034 0 1.5.4 1.5 1.75c0 1.08-.616 1.75-1.5 1.75z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.t3va6px1k {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M19.994 10.687v2.873c0 3.405-3.34 6.44-10.01 6.44C8.074 20 4 19.123 4 13.304V10.44c0-5.844 7.994-6.439 10.009-6.439c6.297 0 6 6.355 5.985 6.686m-4.495-.037c0-1.95-1.035-3.15-2.51-3.15c-.983 0-2.781.719-3.753 1.106L9 8.7v7.8h2v-2.92q.17.063.332.133c.341.143.683.287 1.167.287c1.625 0 3-1.395 3-3.35");
}

</style>
