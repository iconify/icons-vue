<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtcbyicad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ski-helmet" /></template>
<style>
.mtcbyicad {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.25 13.5V18q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h3.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T8.25 18v-1.75h7.5V18q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014H20q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-4.5q0-3.624-2.563-6.187T12 4.75T5.813 7.313T3.25 13.5m3-3.25q0-2.5 2.5-2.5h6.5q2.5 0 2.5 2.5q0 1.036-.732 1.768t-1.768.732h-6.5q-1.036 0-1.768-.732T6.25 10.25");
}

</style>
