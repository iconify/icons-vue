<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hr5l4gb6d"/><path class="dn57_gb_s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:study-participant" /></template>
<style>
.dn57_gb_s {
  d: path("M9.5 16h5v4h-5Z");
}

.hr5l4gb6d {
  d: path("M8.5 6.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0ZM5 21.5v-4A4.5 4.5 0 0 1 9.5 13h5a4.5 4.5 0 0 1 4.5 4.5v4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
