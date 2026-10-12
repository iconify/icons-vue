<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wguz1jb6r"/><path class="x3m23lb9h"/><path class="ct_505bdq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:radial-bar" /></template>
<style>
.ct_505bdq {
  d: path("M12 9.5a2.5 2.5 0 0 1 2.5 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wguz1jb6r {
  d: path("M12 3.5A8.5 8.5 0 1 1 3.5 12");
}

.x3m23lb9h {
  d: path("M12 6.5a5.5 5.5 0 1 1-4.76 8.25");
}

</style>
