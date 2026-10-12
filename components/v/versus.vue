<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqw2mg2qk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:versus" /></template>
<style>
.yqw2mg2qk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 7l3.75 10L11 7m8.75 1.5c-.5-1-1.5-1.5-2.75-1.5c-1.6 0-2.75.9-2.75 2.4c0 3.1 5.5 1.9 5.5 5.1c0 1.6-1.25 2.5-2.85 2.5c-1.25 0-2.4-.6-2.9-1.6");
}

</style>
