<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="yhy4x8bxk"/><path class="nsuypdmbc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:temple-sharp" /></template>
<style>
.nsuypdmbc {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 7h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.yhy4x8bxk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8.65v-.9l.53-.29l8.19-4.42l.53-.29l.53.29l3.44 1.87l.53.29l-.26.54l-.23.47l-.26.54l.58.16l.59.18l.58.16l-.15.58l-.2.84l-.15.58H2.75zm3.5 2.1v6m3.75-6v6m3.75-6v6m-8.1.75h13.1v1.25H20V20h1.25v1.25H2.75V20H4v-1.25h1.25V17.5z");
}

</style>
