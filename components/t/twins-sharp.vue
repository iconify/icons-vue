<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="kqzcvm0zk"/><circle class="jfzmkgu0i"/><path class="g4lptccyb"/><circle class="cs7ft7b3n"/><path class="ts7qwk2vi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:twins-sharp" /></template>
<style>
.cs7ft7b3n {
  cx: 17.5px;
  cy: 8.5px;
  r: 2px;
}

.g4lptccyb {
  d: path("M3 21.25V16.5a3.5 3.5 0 0 1 7 0v4.75Z");
}

.jfzmkgu0i {
  cx: 6.5px;
  cy: 8.5px;
  r: 2px;
}

.kqzcvm0zk {
  d: path("m12 6.5l-1.6-1.55a1.05 1.05 0 0 1 1.6-1.3a1.05 1.05 0 0 1 1.6 1.3Z");
}

.ts7qwk2vi {
  d: path("M14 21.25V16.5a3.5 3.5 0 0 1 7 0v4.75Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
