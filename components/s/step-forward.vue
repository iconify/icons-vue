<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4f6h-bta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:step-forward" /></template>
<style>
.q4f6h-bta {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.25 19V5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T4.5 4.25t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141Q3.75 4.926 3.75 5v14q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T5.25 19m6.934-12.687q-1.243-.871-2.589-.17T8.25 8.361v7.278q-.001 1.517 1.345 2.218t2.589-.17l5.198-3.638q1.067-.747 1.067-2.049t-1.067-2.048z");
}

</style>
