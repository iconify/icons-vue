<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhb3mce5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:national-emblem-sharp" /></template>
<style>
.vhb3mce5g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 20c-4-2.25-5.5-7.25-3.25-12.5M15.75 20c4-2.25 5.5-7.25 3.25-12.5M4.4 11.75L3.25 10.5m2 5L3.5 15m3.75 3.5l-1.5.5m13.85-7.25l1.15-1.25m-2 5l1.75-.5m-3.75 3.5l1.5.5M12.14 8.07l1.03 2.31l.14.32l.35.03l2.51.27l.35.03l-.26.24l-1.88 1.68l-.26.24l.07.34l.53 2.47l.07.34l-.3-.17l-2.19-1.26l-.3-.18l-.3.18l-2.19 1.26l-.3.17l.07-.34l.53-2.47l.07-.34l-.26-.24l-1.88-1.68l-.26-.24l.35-.03l2.51-.27l.35-.03l.14-.32l1.03-2.31l.14-.32z");
}

</style>
