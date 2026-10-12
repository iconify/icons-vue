<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="odsickjnj"/><path class="wup7wyh3k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:vibration-alert-sharp" /></template>
<style>
.odsickjnj {
  d: path("M7.25 6.25h9.5v11.5h-9.5zm1.75 0v-3.5h6v3.5m-6 11.5v3.5h6v-3.5");
}

.wup7wyh3k {
  d: path("M12 9.5V12l1.5 1M4.75 8.5l-2 1.75l2 1.75l-2 1.75l2 1.75m14.5-7l2 1.75l-2 1.75l2 1.75l-2 1.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
