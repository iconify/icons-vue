<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqri-2bzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:office-desk" /></template>
<style>
.bqri-2bzz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.75 3.25h4.5q2.5 0 2.5 2.5v1.5q0 .541-.2 1h2.7q3 0 3 3q0 2.739-2.5 2.977V20.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-6.25H5.75v6.25q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T5 21.25t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-6.273q-2.5-.238-2.5-2.977q0-1.243.879-2.121q.878-.879 2.121-.879h2.7q-.2-.459-.2-1v-1.5q0-2.5 2.5-2.5");
}

</style>
