<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkccxhboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mount" /></template>
<style>
.xkccxhboa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 12H5M11.544 2.13L5.0727 7.61C4.8674 7.78 5.1213 8 5.5287 8H18.4713C18.8787 8 19.1326 7.78 18.9273 7.61L12.456 2.13C12.2523 1.96 11.7477 1.96 11.544 2.13ZM11.544 21.87L5.0727 16.39C4.8674 16.22 5.1213 16 5.5287 16H18.4713C18.8787 16 19.1326 16.22 18.9273 16.39L12.456 21.87C12.2523 22.04 11.7477 22.04 11.544 21.87Z");
}

</style>
