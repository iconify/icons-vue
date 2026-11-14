<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6ldpxbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:status-invisible" /></template>
<style>
.f6ldpxbuo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.322 21.408a9.5 9.5 0 0 1-4.571-.481m-3.469-2.209a9.5 9.5 0 0 1-2.458-4.259m-.18-4.109a9.5 9.5 0 0 1 2.079-4.456M7.985 3.39a9.5 9.5 0 0 1 4.843-.854m3.922 1.237a9.5 9.5 0 0 1 3.477 3.477m1.237 3.922a9.5 9.5 0 0 1-.056 2.15M15.5 18a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
