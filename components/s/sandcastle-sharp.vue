<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ybdpgac7p"/><path class="z00yh7i0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sandcastle-sharp" /></template>
<style>
.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ybdpgac7p {
  d: path("M3.75 20.25V12.5h2.5V14H8.5V8h7v6h2.25v-1.5h2.5v8.25H3.75z");
}

.z00yh7i0b {
  d: path("M10.5 20.75v-4h3v4M12 8V2.75l3.25 1.4L12 5.5");
}

</style>
