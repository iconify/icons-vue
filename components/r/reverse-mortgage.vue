<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ofj-45bvv"/><path class="zvs08ob7l"/><path class="is17_8b8g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:reverse-mortgage" /></template>
<style>
.is17_8b8g {
  d: path("M16.75 14.75L15 16.5l1.75 1.75");
}

.ofj-45bvv {
  d: path("M15.531 21H3V10.5L12 3l9 7.5v3.569M18.731 21h-.8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zvs08ob7l {
  d: path("M7 21v-3.5a2 2 0 0 1 4 0V21m10.5.5V19a2.5 2.5 0 0 0-2.5-2.5h-4");
}

</style>
