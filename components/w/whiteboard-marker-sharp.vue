<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="t2dq00bpq"/><path class="noxv-6nho"/><path class="ya_rorbnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:whiteboard-marker-sharp" /></template>
<style>
.noxv-6nho {
  d: path("m4.79 16.73l2.48 2.48l.88.88l.88-.88l5.49-5.48l.88-.88l-.88-.88l-2.49-2.49l-.88-.88l-.88.88l-5.48 5.49l-.88.88z");
}

.t2dq00bpq {
  d: path("m12.21 9.66l2.13 2.13l1.06 1.06l1.06-1.06l3-3.01l1.06-1.06l-1.06-1.06l-2.12-2.12l-1.06-1.06l-1.06 1.06l-3.01 3l-1.06 1.06z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ya_rorbnd {
  d: path("m5.14 17.08l1.78 1.78l.35.35l-.35.35l-1.07 1.07l-.35.35l-.43-.26l-1.79-1.07l-.43-.26l.29-.4l1.36-1.86l.29-.4z");
}

</style>
