<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ar0_ghomh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:media-folder" /></template>
<style>
.ar0_ghomh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.555 5.055Q1.75 5.861 1.75 7v10.5q0 2.75 2.75 2.75h15q2.75 0 2.75-2.75v-8q0-2.75-2.75-2.75h-8.14L9.586 4.531q-.053-.065-.119-.118t-.142-.089t-.158-.055Q9.084 4.25 9 4.25H4.5q-1.139 0-1.945.805m9.772 5.746l.868.472q1.173.64 1.173 1.976t-1.173 1.976l-.868.473q-1.124.613-2.226-.041T9 13.723v-.946q0-1.281 1.101-1.935t2.226-.041");
}

</style>
