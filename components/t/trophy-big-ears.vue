<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q_jvd8nnh"/><path class="e5ocjco1b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:trophy-big-ears" /></template>
<style>
.e5ocjco1b {
  d: path("M8 4.5c-5.5 0-5.5 7.5.5 5.5M16 4.5c5.5 0 5.5 7.5-.5 5.5M12 12v5m-3 0h6l1 4H8Z");
}

.q_jvd8nnh {
  d: path("M8 3h8v5a4 4 0 0 1-8 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
