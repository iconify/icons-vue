<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mijqayied"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:screw-head-hex" /></template>
<style>
.mijqayied {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 12q-.001 4.039 2.855 6.896T12 21.753t6.895-2.857T21.75 12q.001-4.039-2.855-6.896T12 2.247q-4.04 0-6.895 2.857Q2.249 7.961 2.25 12m13.333-3.955l1.634 2.83q.649 1.125 0 2.25l-1.634 2.83q-.65 1.125-1.949 1.125h-3.268q-1.299 0-1.949-1.125l-1.634-2.83q-.649-1.125 0-2.25l1.634-2.83q.65-1.125 1.949-1.125h3.268q1.299 0 1.949 1.125");
}

</style>
