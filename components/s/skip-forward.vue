<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpw_67v1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:skip-forward" /></template>
<style>
.xpw_67v1r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 19.75q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T19 4.25q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T18.25 5v14q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014M8.184 6.313q-1.243-.871-2.589-.17T4.25 8.361v7.278q-.001 1.517 1.345 2.218t2.589-.17l5.198-3.638q1.067-.747 1.067-2.049t-1.067-2.048z");
}

</style>
