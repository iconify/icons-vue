<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mstthmbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:reaction-celebrate" /></template>
<style>
.mstthmbrm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.352 17.395l2.194-5.85a1.75 1.75 0 0 1 2.876-.623l3.656 3.656a1.75 1.75 0 0 1-.623 2.876l-5.85 2.194a1.75 1.75 0 0 1-2.253-2.253M11.5 7l1-4m1.25 7.25l4.5-4.5M17 13l4-1");
}

</style>
