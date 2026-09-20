<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojh1susxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:swipe" /></template>
<style>
.ojh1susxi {
  fill: currentColor;
  d: path("M21 7.385h-4.384V6.5H19.9q-1.708-1.392-3.704-2.263T12 3.365t-4.196.87Q5.808 5.109 4.1 6.5h3.285v.885H3V3h.885v2.506q1.78-1.36 3.83-2.192T12 2.48t4.285.833t3.83 2.192V3H21zM11.825 21q-.504 0-.948-.186t-.812-.554L5.14 15.346l.48-.467q.227-.208.515-.268q.287-.061.582.012l2.784.687V7q0-.213.143-.357T10 6.5t.357.143T10.5 7v7.27h1.827V10.5q0-.213.143-.357t.357-.143t.357.143t.143.357v3.77h1.846V11.5q0-.213.143-.357t.357-.143t.357.143t.143.357v2.77H18v-.77q0-.213.143-.357T18.5 13t.357.143t.143.357v4q0 1.458-1.021 2.479T15.5 21z");
}

</style>
