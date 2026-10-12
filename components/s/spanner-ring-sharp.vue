<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="prlmlobug"/><circle class="m11btbbwe"/><path class="lhxt83b3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spanner-ring-sharp" /></template>
<style>
.lhxt83b3y {
  d: path("m8.49 18.1l-.64.64l-.21.21l-.29-.08l-.87-.23l-.29-.08l-.08-.29l-.23-.87l-.08-.29l.21-.21l.64-.64l.21-.21l.29.08l.87.23l.29.08l.08.29l.23.87l.08.29zm9.52-13.83a3.5 3.5 0 1 1-1.88-1.32l-2.08 2.94l1.88 1.33Z");
}

.m11btbbwe {
  cx: 7.25px;
  cy: 17.5px;
  r: 3.75px;
}

.prlmlobug {
  d: path("m10.25 15.25l3.94-5.57l-1.88-1.33l-3.94 5.57Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
