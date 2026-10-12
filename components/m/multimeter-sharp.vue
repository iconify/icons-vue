<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bh4biibbp"/><path class="kcf52vx4u"/><circle class="rh1oi0w6a"/><path class="knq-qlk1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:multimeter-sharp" /></template>
<style>
.bh4biibbp {
  d: path("M4.75 2.75h14.5v18.5H4.75z");
}

.kcf52vx4u {
  d: path("M7.75 5.75h8.5V9.5h-8.5Z");
}

.knq-qlk1t {
  d: path("m12 15.25l1.5-1.5");
}

.rh1oi0w6a {
  cx: 12px;
  cy: 15.25px;
  r: 3.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
