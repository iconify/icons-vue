<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yn2yxrpvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:phone-mute" /></template>
<style>
.yn2yxrpvo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.169 14.878A13.5 13.5 0 0 1 3 7.5C3 5 5 3 7.5 3l2.5.5l1.5 4l-2 2q.179.357.397.712m3.933 3.916q.334.204.67.372l2-2l4 1.5l.5 2.5c0 2.5-2 4.5-4.5 4.5c-2.738 0-5.276-.799-7.395-2.18M20.5 3.5l-17 17");
}

</style>
