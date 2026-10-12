<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="fr9wc8ere"/><path class="vhhl-0xxp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:split-view" /></template>
<style>
.fr9wc8ere {
  width: 18.5px;
  height: 16.5px;
  x: 2.75px;
  y: 3.75px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vhhl-0xxp {
  d: path("M12 4.5v15M9 10l-2 2l2 2m6-4l2 2l-2 2");
}

</style>
