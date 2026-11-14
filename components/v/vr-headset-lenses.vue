<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apfdt8vir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:vr-headset-lenses" /></template>
<style>
.apfdt8vir {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.5 4.25h13q1.76 0 3.005 1.245T22.75 8.5v7q0 1.76-1.245 3.005T18.5 19.75h-4q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T13.75 19q0-1.75-1.75-1.75T10.25 19q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-4q-1.76 0-3.005-1.245T1.25 15.5v-7q0-1.76 1.245-3.005T5.5 4.25M7.75 8q-3.5 0-3.5 3.5t3.5 3.5t3.5-3.5T7.75 8m5 3.5q0 3.5 3.5 3.5t3.5-3.5t-3.5-3.5t-3.5 3.5");
}

</style>
