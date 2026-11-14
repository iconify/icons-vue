<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xc2o8ft2e"/><path class="wupi7lhns"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:willow-tree" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wupi7lhns {
  d: path("M12 6c-2.5 1-4 4-4 9m4-9c2.5 1 4 4 4 9");
}

.xc2o8ft2e {
  d: path("M4 17C4 8 7.5 3 12 3s8 5 8 14M12 6v15.5");
}

</style>
