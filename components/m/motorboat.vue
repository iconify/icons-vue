<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxwrdqb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:motorboat" /></template>
<style>
.vxwrdqb2u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 13.75V8.5q0-.75.75-.75h6q.75 0 1.05.69l2.4 5.37q.3.69-.45.69h-9q-.75 0-.75-.75m2-3h1.5m2 0h1.5m-8.5 3.75h15L20 18.25a1.5 1.5 0 0 1-1.42 1H7.67a1.5 1.5 0 0 1-1.42-1Zm-2.75-4h1q.75 0 .75.75v2.5q0 .75-.75.75h-1q-.75 0-.75-.75v-2.5q0-.75.75-.75m.5 4V18");
}

</style>
