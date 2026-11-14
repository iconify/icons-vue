<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qmlu21bes"/><path class="fh6y1kizw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:price-check-station" /></template>
<style>
.fh6y1kizw {
  d: path("M9.5 6.5h7v6h-7L7 9.5Zm.25 3h.01m4.99 7.75v4.25M17 17.25v4.25m2.25-4.25v4.25m2.25-4.25v4.25");
}

.qmlu21bes {
  d: path("M12 2.5v2m-.1 10H3.5v-10h17v9.9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
