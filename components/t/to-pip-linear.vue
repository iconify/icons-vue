<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="i2iiwfb2x"/><path class="jcusk6gmi"/><path class="yq3ukacfg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:to-pip-linear" /></template>
<style>
.i2iiwfb2x {
  d: path("M11 21H10C6.22876 21 4.34315 21 3.17157 19.8284C2 18.6569 2 16.7712 2 13V11C2 7.22876 2 5.34315 3.17157 4.17157C4.34315 3 6.22876 3 10 3H14C17.7712 3 19.6569 3 20.8284 4.17157C22 5.34315 22 7.22876 22 11");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jcusk6gmi {
  d: path("M17 21H18C19.8856 21 20.8284 21 21.4142 20.4142C22 19.8284 22 18.8856 22 17C22 15.1144 22 14.1716 21.4142 13.5858C20.8284 13 19.8856 13 18 13H17C15.1144 13 14.1716 13 13.5858 13.5858C13 14.1716 13 15.1144 13 17C13 18.8856 13 19.8284 13.5858 20.4142C14.1716 21 15.1144 21 17 21Z");
}

.yq3ukacfg {
  stroke-linejoin: round;
  d: path("M8.5 11.5H11.5V8.5M11.5 11.5L7.5 7.5");
}

</style>
