<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnvceuvea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:people-agree" /></template>
<style>
.bnvceuvea {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 8.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM3 21c0-3.5 2-6.5 5-6.5c1.68 0 3.046.941 3.923 2.383m1.036 3.254q.04.425.041.863m.75-15.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm.75 6.25a8 8 0 0 1 2-.25c1.662 0 2.874.451 3.419 1.353M14.75 18l2 2L21 15.75");
}

</style>
