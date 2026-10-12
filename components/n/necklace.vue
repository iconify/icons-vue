<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vo4u71bpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:necklace" /></template>
<style>
.vo4u71bpk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 2.75c.5 7 3.5 11 7.75 11.75c4.25-.75 7.25-4.75 7.75-11.75m-7.22 12.78l1.94 1.94q.53.53.02 1.08l-1.98 2.15q-.51.55-1.02 0l-1.98-2.15Q9 18 9.53 17.47l1.94-1.94q.53-.53 1.06 0");
}

</style>
