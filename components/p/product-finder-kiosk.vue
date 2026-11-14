<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b9xpxjbmg"/><path class="apzkjmr9m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:product-finder-kiosk" /></template>
<style>
.apzkjmr9m {
  d: path("M12 12c-2-2-3-3.5-3-4.75a3 3 0 0 1 6 0C15 8.5 14 10 12 12Zm0-4.75h.01");
}

.b9xpxjbmg {
  d: path("M4.5 2.5h15l-1 11.5h-13ZM10 14h4v5.5h-4Zm-3.5 7.5h11");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
