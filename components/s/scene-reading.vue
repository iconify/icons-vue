<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ychj5_j3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:scene-reading" /></template>
<style>
.ychj5_j3r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12c-1.75-1.25-4.75-1.5-8.5-1v8.5c3.75-.5 6.75-.25 8.5 1c1.75-1.25 4.75-1.5 8.5-1V11c-3.75-.5-6.75-.25-8.5 1m0 0v8.5m6.53-16.405l.348.554a1.5 1.5 0 0 0 .473.473l.554.348a.626.626 0 0 1 0 1.06l-.554.348a1.5 1.5 0 0 0-.473.473l-.348.554a.626.626 0 0 1-1.06 0l-.348-.554a1.5 1.5 0 0 0-.473-.473l-.554-.348a.626.626 0 0 1 0-1.06l.554-.348a1.5 1.5 0 0 0 .473-.473l.348-.554a.626.626 0 0 1 1.06 0");
}

</style>
