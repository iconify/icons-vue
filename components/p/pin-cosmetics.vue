<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dpfpff3ve"/><path class="mppw7u4jt"/><path class="wmzschbip"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-cosmetics" /></template>
<style>
.dpfpff3ve {
  d: path("m8.172 9.586l4.242 4.242l-5.657 5.657l-4.242-4.242Z");
}

.mppw7u4jt {
  d: path("m11.177 7.641l3.182 3.182l-2.475 2.475l-3.182-3.182Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wmzschbip {
  d: path("m11.707 8.172l2.829-2.829l3.889.354l-4.597 4.596ZM19 22l-2.25-2.75a2.75 2.75 0 1 1 4.5 0Z");
}

</style>
