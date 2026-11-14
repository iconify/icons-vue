<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rz0x01bic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:timeline-vertical" /></template>
<style>
.rz0x01bic {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.75 2.5v1.31q2 .345 2 2.69t-2 2.69v5.62q2 .345 2 2.69t-2 2.69v1.31q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T6 22.25t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-1.31q-2-.345-2-2.69t2-2.69V9.19q-2-.345-2-2.69t2-2.69V2.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q5.926 1.75 6 1.75t.146.014t.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146m12.5 1h-6.5q-2.5 0-2.5 2.5v1q0 2.5 2.5 2.5h6.5q1.036 0 1.768-.732T21.75 7V6q0-1.036-.732-1.768T19.25 3.5m-6.5 11h6.5q1.036 0 1.768.732T21.75 17v1q0 1.036-.732 1.768t-1.768.732h-6.5q-1.036 0-1.768-.732T10.25 18v-1q0-2.5 2.5-2.5");
}

</style>
