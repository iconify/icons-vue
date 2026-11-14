<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vd--1p-4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pet-euthanasia" /></template>
<style>
.vd--1p-4k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.75 3.5q0-2 5.25-2t5.25 2t-5.25 2t-5.25-2M6.5 9q0-2.5 2.5-2.5q1.036 0 1.768.732T11.5 9t-.732 1.768T9 11.5q-2.5 0-2.5-2.5M15 6.5q-2.5 0-2.5 2.5t2.5 2.5q1.036 0 1.768-.732T17.5 9t-.732-1.768T15 6.5m-13 6Q2 10 4.5 10q1.036 0 1.768.732T7 12.5t-.732 1.768T4.5 15Q2 15 2 12.5M19.5 10Q17 10 17 12.5t2.5 2.5t2.5-2.5t-2.5-2.5M8.034 14.411Q6.25 15.66 6.25 17.5t1.784 3.089Q9.693 21.75 12 21.75t3.966-1.161Q17.75 19.34 17.75 17.5t-1.784-3.089Q14.307 13.25 12 13.25t-3.966 1.161");
}

</style>
