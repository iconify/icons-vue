<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v01drvbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mail-spark-outline-sharp" /></template>
<style>
.v01drvbcs {
  fill: currentColor;
  d: path("m12 11l7.692-5H4.308zm-.083 8H3V5h18v7.077h-1V6.904l-8 5.212l-8-5.212V18h7.917zm6.487 3.5q-.15 0-.2-.15q-.362-1.39-1.359-2.387t-2.387-1.36q-.15-.05-.15-.2q0-.174.15-.2q1.39-.36 2.387-1.358q.997-.997 1.359-2.387q.05-.15.2-.15q.169 0 .2.15q.361 1.39 1.358 2.387t2.388 1.359q.15.025.15.2q0 .15-.15.2q-1.39.362-2.388 1.359t-1.358 2.387q-.025.15-.2.15");
}

</style>
