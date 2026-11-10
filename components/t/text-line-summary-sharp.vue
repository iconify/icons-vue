<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ogrz9fbvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:text-line-summary-sharp" /></template>
<style>
.ogrz9fbvr {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 13H15M6 8H22M6 3H22M18.311 21.27L21 18.75L18.284 16.2M21 18.75H3V2");
}

</style>
