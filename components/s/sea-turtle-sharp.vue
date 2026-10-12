<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="q95h2vvqj"/><circle class="w-rip4ezp"/><path class="pbyi-0-7g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sea-turtle-sharp" /></template>
<style>
.pbyi-0-7g {
  d: path("M12 7a5 6.5 0 0 1 5 6.5a5 6.5 0 0 1-5 6.5a5 6.5 0 0 1-5-6.5A5 6.5 0 0 1 12 7Zm0 3v7");
}

.q95h2vvqj {
  d: path("M6.94 10L3.87 7.5L3.25 7l-.14.79l-.22 1.17l-.14.79l.67.43l2.97 1.89l.67.43l.19-.78l.12-.44l.19-.78zm10.12 0l3.07-2.5l.62-.5l.14.79l.22 1.17l.14.79l-.67.43l-2.97 1.89l-.67.43l-.19-.78l-.12-.44l-.19-.78zm-9.94 6.9l-2.43 2.2l-.44.4l.58.13l2.09.49l.58.13l.36-.48l.58-.79l.36-.48l-.32-.51l-.6-.98l-.32-.51zm9.76 0l2.43 2.2l.44.4l-.58.13l-2.09.49l-.58.13l-.36-.48l-.58-.79l-.36-.48l.32-.51l.6-.98l.32-.51z");
}

.w-rip4ezp {
  cx: 12px;
  cy: 5.25px;
  r: 1.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
