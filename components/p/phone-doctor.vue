<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l1tv0xafw"/><path class="xzcs0vr8n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:phone-doctor" /></template>
<style>
.l1tv0xafw {
  d: path("M6 2.5h12v19H6ZM10.5 5h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xzcs0vr8n {
  d: path("M8.5 6v2.5c0 1.75 1.25 3 2.75 3S14 10.25 14 8.5V6m-2.75 5.5v1c0 1.25 1 2 2.25 2s2-1 2-1.75m-1.25-1.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

</style>
