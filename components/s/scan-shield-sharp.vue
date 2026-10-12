<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqayq8cgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:scan-shield-sharp" /></template>
<style>
.wqayq8cgq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.5V2.75H7.5m9 0h4.75V7.5m0 9v4.75H16.5m-9 0H2.75V16.5M12 6.5l4.5 1.6v3.65c0 2.9-1.85 5-4.5 6.25c-2.65-1.25-4.5-3.35-4.5-6.25V8.1ZM4.25 12h15.5");
}

</style>
