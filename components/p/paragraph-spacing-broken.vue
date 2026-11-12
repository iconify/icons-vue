<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tlstgmb9z"/><path class="bq0ypf47a"/><path class="iim04tfhn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paragraph-spacing-broken" /></template>
<style>
.bq0ypf47a {
  d: path("M4 3H20");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iim04tfhn {
  d: path("M9 8.5L12 5.5L15 8.5M12 5.5V18.5M9 15.5L12 18.5L15 15.5");
}

.tlstgmb9z {
  d: path("M4 21H13M17 21H20");
}

</style>
