<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ik0twvfwg"/><path class="zlllb2_jv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:video-gallery-sharp" /></template>
<style>
.ik0twvfwg {
  d: path("M2.75 2.75h7.75v7.75H2.75zm10.75 0h7.75v7.75H13.5zM2.75 13.5h7.75v7.75H2.75zm10.75 0h7.75v7.75H13.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zlllb2_jv {
  d: path("m5.93 5.25l1.89 1.13l.43.25l-.43.25L5.93 8l-.43.25V5z");
}

</style>
