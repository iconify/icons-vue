<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="qr9d7g7hg"/><path class="fchma77yp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:valve-sharp" /></template>
<style>
.fchma77yp {
  d: path("M8.5 11h7v10.25h-7zm3.5 0V6.5M6.75 3.25h10.5v3H6.75zm-1.5 10.5v5m13.5-5v5");
}

.qr9d7g7hg {
  d: path("M2.75 13.75h18.5v5H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
