<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="yohxqabuf"/><path class="i1ovlac-p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wiper-blade-sharp" /></template>
<style>
.i1ovlac-p {
  d: path("m6.6 17.4l6.65-6.65m-1.9-1.7l7.55-5.6l.6-.45l.49.57l.52.61l.49.57l-.6.45l-7.55 5.6l-.6.45l-.49-.57l-.52-.61l-.49-.57z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yohxqabuf {
  cx: 5px;
  cy: 19px;
  r: 2.25px;
}

</style>
