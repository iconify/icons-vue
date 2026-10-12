<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="uv0qq0akh"/><path class="i66-bd_qs"/><path class="b7g44gbpt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:packing-list-sharp" /></template>
<style>
.b7g44gbpt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 7.5h4.5m-4.5 4h3M14 16h7.25v5.25H14zm1.75 0v-2.25h3.75V16");
}

.i66-bd_qs {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.5 7.5h.01m-.01 4h.01m-.01 4h.01");
}

.uv0qq0akh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.75 21.25h-7V2.75h14.5v8.75");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
