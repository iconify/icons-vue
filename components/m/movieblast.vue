<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rsyq723xm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:movieblast" /></template>
<style>
.rsyq723xm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.275 5.697L5.5 24.495m19.11-16L8.835 27.293m.986-1.175L6.486 23.32m1.972-2.35l3.335 2.799m1.972-2.35L10.43 18.62m1.971-2.35l3.336 2.799m1.972-2.35l-3.336-2.798m1.972-2.35l3.335 2.798m1.972-2.35l-3.335-2.798m1.971-2.35l3.336 2.799m15.541 11.037L23.39 39.505m19.11-16L26.725 42.303m.986-1.173l-3.335-2.8m1.971-2.349l3.336 2.799m1.972-2.35l-3.336-2.799m1.972-2.35l3.335 2.799m1.972-2.35l-3.335-2.798m1.972-2.35l3.335 2.798m1.972-2.35l-3.336-2.798m1.972-2.35l3.336 2.799m-30.134-.42l14.554 12.212m-3.868-24.946L36.62 23.74m-20.779.131l6.615-7.883L24 24.001l8.16.129l-6.616 7.883");
}

</style>
