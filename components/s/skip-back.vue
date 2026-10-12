<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cc5iawb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:skip-back" /></template>
<style>
.cc5iawb9m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.81 5.74l-7.62 5.27q-1.44.99 0 1.98l7.62 5.27q1.44.99 1.44-.76v-11q0-1.75-1.44-.76M4.75 4.75v14.5");
}

</style>
