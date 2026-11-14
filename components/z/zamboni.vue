<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsamxdb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:zamboni" /></template>
<style>
.bsamxdb6i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 8.25V4.5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014h7q.1 0 .197.026q.097.027.183.078q.087.05.157.122t.119.16l2.285 4.114h2.434q3.375 0 3.375 3.375v2.25q0 3.355-3.334 3.375q.334.708.334 1.75q0 3.25-3.25 3.25T12.75 19q0-1.042.334-1.75H9.747q.503.771.503 1.75q0 1.346-.952 2.299q-.951.952-2.298.952t-2.298-.952T3.75 19q0-1.017.543-1.809q-2.543-.387-2.543-3.316v-2.25q0-3.375 3.375-3.375zm7.309-3H7.25v3h7.475z");
}

</style>
