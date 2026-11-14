<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tr7y4kbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:vr-headset-battery" /></template>
<style>
.tr7y4kbvx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 4h9a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2h-2.25L13 10.5h-2L9.75 13H7.5a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2m-5 4.5h3m13 0h3M15 17h4.5a1 1 0 0 1 1 1v.5h1V20h-1v.5a1 1 0 0 1-1 1H15a1 1 0 0 1-1-1V18a1 1 0 0 1 1-1m2.25 0v4.5");
}

</style>
