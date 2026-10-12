<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pw7p-85ys"/><path class="xzqlhfbsw"/><path class="ylwmg5vdw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mask-photo-sharp" /></template>
<style>
.pw7p-85ys {
  d: path("M2.75 3.75h18.5v16.5H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xzqlhfbsw {
  d: path("M12 7a5 5 0 0 0 0 10Z");
}

.ylwmg5vdw {
  d: path("M17 12a5 5 0 1 1-10 0a5 5 0 1 1 10 0");
}

</style>
