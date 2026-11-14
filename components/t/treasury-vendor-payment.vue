<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ek5-jhc_j"/><path class="ybor9pbjq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:treasury-vendor-payment" /></template>
<style>
.ek5-jhc_j {
  d: path("M8.5 7h-3l-3 3.5v5h6M8.5 4h13v11.5h-13Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ybor9pbjq {
  d: path("M16.25 8.25c-.05-.51-.56-.75-1.25-.75c-.84 0-1.35.42-1.25 1c-.1 1.31 2.6.77 2.5 2.5c.1.55-.47 1-1.25 1c-.72 0-1.23-.3-1.25-.75M15 6.5v1m0 4.5v1M4.25 17a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm11 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

</style>
