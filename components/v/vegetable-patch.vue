<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tihsgwbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:vegetable-patch" /></template>
<style>
.tihsgwbxd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.761 11h12.311a1.75 1.75 0 0 1 1.66 2.303l-1.833 5.5A1.75 1.75 0 0 1 17.239 20H4.928a1.75 1.75 0 0 1-1.66-2.303l1.833-5.5A1.75 1.75 0 0 1 6.761 11m.739 0V7m0 0L6 4.75M7.5 7L9 4.75M13.5 11V7m0 0L12 4.75M13.5 7L15 4.75M19.5 11V7m0 0L18 4.75M19.5 7L21 4.75");
}

</style>
