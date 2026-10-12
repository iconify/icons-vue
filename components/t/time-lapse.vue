<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmfm66b1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:time-lapse" /></template>
<style>
.jmfm66b1y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.81 2.79a9.3 9.3 0 0 1 3.1.83m1.4.8a9.3 9.3 0 0 1 2.27 2.27m.8 1.4a9.3 9.3 0 0 1 .83 3.1m0 1.62a9.3 9.3 0 0 1-.83 3.1m-.8 1.4a9.3 9.3 0 0 1-2.27 2.27m-1.4.8a9.3 9.3 0 0 1-3.1.83m-1.62 0a9.3 9.3 0 0 1-3.1-.83m-1.4-.8a9.3 9.3 0 0 1-2.27-2.27m-.8-1.4a9.3 9.3 0 0 1-.83-3.1m0-1.62a9.3 9.3 0 0 1 .83-3.1m.8-1.4a9.3 9.3 0 0 1 2.27-2.27m1.4-.8a9.3 9.3 0 0 1 3.1-.83M12 7.5V12l3 2");
}

</style>
