<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ty1bb9tkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sailing-dinghy" /></template>
<style>
.ty1bb9tkt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.158 15.5h13.984a1.307 1.307 0 0 1 1.108 2l-.809 1.295a1.5 1.5 0 0 1-1.272.705H6.681a1.5 1.5 0 0 1-1.129-.512L4.25 17.5a1.206 1.206 0 0 1 .908-2M11 2.5v13M11 4l8 8.75h-8M8.25 9.125v2.125a1.5 1.5 0 0 1-1.5 1.5h-.875a1.283 1.283 0 0 1-1.073-1.987l1.461-2.231a1.082 1.082 0 0 1 1.987.593");
}

</style>
