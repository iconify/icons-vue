<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="goiz_9b_e"/><path class="we1jfrbqn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:thermostat-down" /></template>
<style>
.goiz_9b_e {
  d: path("M6.551 19.782a9.5 9.5 0 1 1 10.898 0M12 2.5v2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.we1jfrbqn {
  d: path("m8 10.5l4 4l4-4");
}

</style>
