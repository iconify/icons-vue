<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ynd9hpwnz"/><path class="m1-v7ac9a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:treasury-approval-chain" /></template>
<style>
.m1-v7ac9a {
  d: path("m3.75 18.25l1 1l1.75-2m4-5.25l1 1l1.75-2m4-5.25l1 1l1.75-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ynd9hpwnz {
  d: path("M2.25 18.25a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM9 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm6.75-6.25a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM7.5 16.25L9.75 14m4.5-4l2.25-2.25");
}

</style>
