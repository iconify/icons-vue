<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="a51c0jbmt"/><path class="i3-jvr20i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:puzzle-cube-sharp" /></template>
<style>
.a51c0jbmt {
  d: path("m13.31 3.48l5.88 3.29l1.31.73v9l-1.31.73l-5.88 3.29l-1.31.73l-1.31-.73l-5.88-3.29l-1.31-.73v-9l1.31-.73l5.88-3.29L12 2.75z");
}

.i3-jvr20i {
  d: path("M4.25 7.92L12 12.25l7.75-4.33M12 12.25v8.4M8.52 5.55l6.96 3.9m0-3.9l-6.96 3.9");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
