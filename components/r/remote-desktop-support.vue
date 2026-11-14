<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ns0c7bbfw"/><path class="a1kq-4btw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:remote-desktop-support" /></template>
<style>
.a1kq-4btw {
  d: path("m12 7.75l1.691.846a.629.629 0 0 1-.066 1.154l-.783.285a1.5 1.5 0 0 0-.853.789l-.364.801a.564.564 0 0 1-1.054-.073l-.618-2.086A1.456 1.456 0 0 1 12 7.75m.5 2.75l2.5 2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ns0c7bbfw {
  d: path("M6.875 3.5h10.25A4.375 4.375 0 0 1 21.5 7.875v4.25a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 12.125v-4.25A4.375 4.375 0 0 1 6.875 3.5M12 16.5v4m-4 0h8");
}

</style>
