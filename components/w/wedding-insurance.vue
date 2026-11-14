<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wiv-21r5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:wedding-insurance" /></template>
<style>
.wiv-21r5s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m6.812 4.697l.432-.862Q7.787 2.751 9 2.75q1.213.001 1.756 1.086l.432.861q.724 1.451-.422 2.597l-.236.236q-.633.634-1.53.634T7.47 7.53l-.236-.236q-1.146-1.146-.422-2.596zM3.25 14.5q0-2.382 1.684-4.066T9 8.75q1.672 0 3 .83q1.328-.83 3-.83q2.382 0 4.066 1.684T20.75 14.5t-1.684 4.066T15 20.25q-1.672 0-3-.83q-1.328.83-3 .83q-2.382 0-4.066-1.684T3.25 14.5");
}

</style>
