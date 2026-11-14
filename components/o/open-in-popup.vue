<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ee5f5wbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:open-in-popup" /></template>
<style>
.ee5f5wbgd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.5 17.75H5q-3.25 0-3.25-3.25V5q0-1.346.952-2.298T5 1.75h11.5q3.25 0 3.25 3.25v4.5q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146V7.25h-15v7.25q0 1.75 1.75 1.75h4.5q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014m-6.25-12h15V5q0-1.75-1.75-1.75H5q-.725 0-1.237.513Q3.25 4.275 3.25 5zm12.75 6h2q1.76 0 3.005 1.245T22.25 16v2q0 1.76-1.245 3.005T18 22.25h-2q-1.76 0-3.005-1.245T11.75 18v-2q0-1.76 1.245-3.005T16 11.75");
}

</style>
