<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="yqmcxk7ec"/><path class="qz-djccyv"/><path class="hhx-69jmu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:skyline-sharp" /></template>
<style>
.hhx-69jmu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.5 4.5V2.75");
}

.qz-djccyv {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.9 11.5h.01m4.59-1h.01M13.5 14h.01m5.09 1.5h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.yqmcxk7ec {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.85V13l.28-.28l1.44-1.44l.28-.28l.28.28l1.44 1.44l.28.28V8H11v-.75h1V4.5h3v2.75h1v3l.37.14l4.51 1.72l.37.14v9H2.75zm4-7.85v8.25M11 8v13.25m5-11v11");
}

</style>
