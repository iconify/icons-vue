<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ua_8dab4r"/><path class="ja_0od71p"/><path class="pl0d48o7j"/><path class="wddphhbzi"/><path class="hmcd_kbpr"/><path class="u08gxpbrl"/><path class="rochh0b5x"/><path class="kwrkgxb3p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:structure-linear" /></template>
<style>
.hmcd_kbpr {
  d: path("M8 19H16");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ja_0od71p {
  d: path("M22 5C22 6.65685 20.6569 8 19 8C17.3431 8 16 6.65685 16 5C16 3.34315 17.3431 2 19 2C20.6569 2 22 3.34315 22 5Z");
}

.kwrkgxb3p {
  d: path("M5 16L5 8");
}

.pl0d48o7j {
  d: path("M8 19C8 20.6569 6.65685 22 5 22C3.34315 22 2 20.6569 2 19C2 17.3431 3.34315 16 5 16C6.65685 16 8 17.3431 8 19Z");
}

.rochh0b5x {
  d: path("M19 16L19 8");
}

.u08gxpbrl {
  d: path("M8 5H16");
}

.ua_8dab4r {
  d: path("M8 5C8 6.65685 6.65685 8 5 8C3.34315 8 2 6.65685 2 5C2 3.34315 3.34315 2 5 2C6.65685 2 8 3.34315 8 5Z");
}

.wddphhbzi {
  d: path("M22 19C22 20.6569 20.6569 22 19 22C17.3431 22 16 20.6569 16 19C16 17.3431 17.3431 16 19 16C20.6569 16 22 17.3431 22 19Z");
}

</style>
