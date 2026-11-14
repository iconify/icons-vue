<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zd6ol7bkz"/><path class="f-14_lnon"/><path class="mr48r514n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:time-off-bank" /></template>
<style>
.f-14_lnon {
  d: path("m13 9.25l2.25-2.5l1.25 3ZM7 19.5v2m8.5-2v2m.75-8.75h.01m-7.51-1h3.5M8 4.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

.mr48r514n {
  d: path("M10.5 3.5v1l.75.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zd6ol7bkz {
  d: path("M3.5 14.5a8 5.5 0 1 0 16 0a8 5.5 0 1 0-16 0Zm16-1.75h2v3.5h-2Z");
}

</style>
