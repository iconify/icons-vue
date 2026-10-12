<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dbgvcxwad"/><circle class="kb86c-bek"/><circle class="bu75h2b-b"/><path class="a9umj-bxo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:nerd-sharp" /></template>
<style>
.a9umj-bxo {
  d: path("M11 10.25h2M8.5 14.5h7m-4.75 0V17h2.5v-2.5");
}

.bu75h2b-b {
  cx: 15.25px;
  cy: 10.25px;
  r: 2.25px;
}

.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.kb86c-bek {
  cx: 8.75px;
  cy: 10.25px;
  r: 2.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
