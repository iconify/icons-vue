<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mp_oh0o1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mushroom-lamp" /></template>
<style>
.mp_oh0o1g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 11q.001-3.831 2.71-6.539T12 1.753t6.54 2.708T21.25 11q0 .074-.014.146q-.015.073-.043.141t-.069.129t-.093.114q-.053.052-.114.093q-.062.042-.13.07t-.14.043t-.147.014h-7.75v5.523q1.996.128 3.498.947Q18.25 19.312 18.25 21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-11q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T5.75 21q0-1.688 2.002-2.78q1.502-.819 3.498-.947V11.75H3.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q2.75 11.074 2.75 11");
}

</style>
