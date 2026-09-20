<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="b-awksbuy"/><path clip-rule="evenodd" class="u9o5gobvl"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rpl-background" /></template>
<style>
.b-awksbuy {
  fill: var(--svg-color--ff7534, #ff7534);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.u9o5gobvl {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M20 12a8 8 0 1 1-16 0a8 8 0 0 1 16 0m-.47 0a7.53 7.53 0 0 1-12.298 5.828l-.045.042l-.344-.374l.005-.005l-.124-.119l-.021.02l-.345-.373l.016-.015l-.11-.125l-.021.02l-.343-.375l.048-.044A7.53 7.53 0 1 1 19.53 12M5.955 16.472A7.518 7.518 0 1 1 7.24 17.82l2.644-2.43l-.343-.375l-2.685 2.469l-.125-.12l3.232-2.981l-.344-.374l-3.238 2.988l-.109-.126l2.646-2.419l-.343-.375zm3.193-4.292l.768-.92l1.125-.28c.627-.82 2.369-2.421 4.316-2.283c.151.548-.096 2.144-2.293 4.143l-.238 1.059l-.952.866l-.379-1.104a1.54 1.54 0 0 1-.703-.084l-.404.42l-.411-.42l.41-.38c-.047-.035-.144-.205-.159-.612zm4.095-.598a.628.628 0 1 1-.89-.887a.628.628 0 0 1 .89.887");
}

</style>
