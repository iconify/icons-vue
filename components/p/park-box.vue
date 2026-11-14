<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwnq8ebme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:park-box" /></template>
<style>
.lwnq8ebme {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m6.352 7.398l-2.25 3.5v.001q-.802 1.247-.091 2.549t2.194 1.302H19.25q2.5 0 2.5-2.5v-3.5q0-1.036-.732-1.768T19.25 6.25H8.455q-1.365 0-2.103 1.148M21 16.25H3q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T2.25 17t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h18q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 16.25");
}

</style>
