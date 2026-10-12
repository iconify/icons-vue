<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="cvkydwb2g"/><path class="jmswzccdb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:prompt-injection-sharp" /></template>
<style>
.cvkydwb2g {
  d: path("M2.75 9.25h13v12h-13z");
}

.jmswzccdb {
  d: path("m6.25 13l2 2l-2 2m4.25 0h2m7.46-10.84l-2.42 2.42l-.35.35l-.35-.35l-1.42-1.42l-.35-.35l.35-.35l2.42-2.42l.35-.35l.35.35l1.42 1.42l.35.35zm-3.83 1.71L12 12m7.25-7.25l2-2");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
