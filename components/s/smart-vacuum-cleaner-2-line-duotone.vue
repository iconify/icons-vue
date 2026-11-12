<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gshkn9qqt"/><path class="srug0hb7t"/><path class="wyvi3vbxo"/><path class="ltt5oydcb"/><path class="phgew86rc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smart-vacuum-cleaner-2-line-duotone" /></template>
<style>
.gshkn9qqt {
  d: path("M22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2C17.5228 2 22 6.47715 22 12Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ltt5oydcb {
  d: path("M2 22L4.92893 19.0711");
}

.phgew86rc {
  d: path("M22 22.0001L19.0711 19.0711");
}

.srug0hb7t {
  d: path("M15 9C15 10.6569 13.6569 12 12 12C10.3431 12 9 10.6569 9 9C9 7.34315 10.3431 6 12 6C13.6569 6 15 7.34315 15 9Z");
}

.wyvi3vbxo {
  d: path("M12 18V16");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
