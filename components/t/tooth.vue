<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nl9-1-zkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tooth" /></template>
<style>
.nl9-1-zkw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.5 2.75q1.205 0 2.842.599q1.095.401 1.658.401t1.658-.401q1.637-.599 2.842-.599q4.25 0 4.25 5.25q0 1.66-.825 4.183q-.506 1.548-.69 2.464l-1 5q-.308 1.541-1.735 1.541t-1.732-1.525l-.998-4.49q-.238-.923-1.77-.923t-1.77.923l-.995 4.474q-.308 1.541-1.735 1.541t-1.735-1.541l-1-5q-.184-.916-.69-2.464Q3.25 9.66 3.25 8q0-5.25 4.25-5.25");
}

</style>
