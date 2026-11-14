<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t_jz6xylu"/><path class="fey1yxb1v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sign-holder-counter" /></template>
<style>
.fey1yxb1v {
  d: path("M7.413 17h5.733a1.5 1.5 0 0 1 .671.158L17 18.75a.924.924 0 0 1-.413 1.75h-5.733a1.5 1.5 0 0 1-.671-.158L7 18.75A.924.924 0 0 1 7.413 17m6.087 0L15 3M6.5 7h6M6 10.5h5.5m-6 3.5h5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t_jz6xylu {
  d: path("M6.348 3h6.983a1.5 1.5 0 0 1 1.491 1.66l-1.178 11A1.5 1.5 0 0 1 12.152 17H5.169a1.5 1.5 0 0 1-1.491-1.66l1.178-11A1.5 1.5 0 0 1 6.348 3");
}

</style>
