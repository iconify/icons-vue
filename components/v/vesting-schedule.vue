<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_p6hlnxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:vesting-schedule" /></template>
<style>
.j_p6hlnxj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12V4a8 8 0 0 1 8 8Zm0-4l4 4m-3-7.25L19.25 11m.25 4h.01m-1.76 2.75h.01M15 19.5h.01M12 20h.01M9 19.5h.01m-2.76-1.75h.01M4.5 15h.01M4 12h.01m.49-3h.01m1.74-2.75h.01M9 4.5h.01");
}

</style>
