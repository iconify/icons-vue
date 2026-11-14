<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wspi74n0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mast-step" /></template>
<style>
.wspi74n0b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 2.25q3.25 0 3.25 3.25v8q0 1.042-.334 1.75h.834q2.5 0 2.5 2.5v.5q0 .564-.127 1H21.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T1.75 20t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h3.377q-.127-.436-.127-1v-.5q0-2.5 2.5-2.5h.834q-.334-.708-.334-1.75v-8q0-3.25 3.25-3.25");
}

</style>
