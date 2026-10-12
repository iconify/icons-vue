<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fta-2yb9l"/><path class="r0-aay79l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tunic-sharp" /></template>
<style>
.fta-2yb9l {
  d: path("M9.5 2.75h6l.92.39l1.66.72l.92.39l.49.87l1.27 2.26l.49.87l-.98.2l-1.79.35l-.98.2l.2.98l2.1 10.29l.2.98H4l.2-.98L6.3 9.98L6.5 9l-.98-.2l-1.79-.35l-.98-.2l.49-.87l1.27-2.26l.49-.87l.92-.39l1.66-.72l.92-.39z");
}

.r0-aay79l {
  d: path("M10 2.75v3h4v-3m-2 3v2m-5 13.5v-3m10 3v-3M5.8 12.5h12.4");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
