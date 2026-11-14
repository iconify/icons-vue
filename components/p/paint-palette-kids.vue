<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omn1wtbcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:paint-palette-kids" /></template>
<style>
.omn1wtbcl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 2.25q4.374 0 7.299 2.492Q22.25 7.256 22.25 11q0 3.75-4.25 3.75q-.967 0-1.179.529q-.263.659.35 1.886q.017.035.031.072q.749 1.996-1.099 3.366Q14.554 21.75 12 21.75q-4.389 0-7.333-2.835Q1.75 16.106 1.75 12t2.917-6.915Q7.611 2.25 12 2.25M8.5 5.5Q6 5.5 6 8t2.5 2.5T11 8T8.5 5.5M12 8q0 2.5 2.5 2.5q1.036 0 1.768-.732T17 8t-.732-1.768T14.5 5.5Q12 5.5 12 8m-7.75 5.25q0 2.5 2.5 2.5t2.5-2.5t-2.5-2.5t-2.5 2.5m7.75.25q-2.5 0-2.5 2.5t2.5 2.5q1.036 0 1.768-.732T14.5 16t-.732-1.768T12 13.5");
}

</style>
