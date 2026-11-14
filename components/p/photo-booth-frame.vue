<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmm7evbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:photo-booth-frame" /></template>
<style>
.qmm7evbsb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.5 1.75h-9q-1.76 0-3.005 1.245T3.25 6v7q0 1.76 1.245 3.005T7.5 17.25h2.25v3.25q0 1.75 1.75 1.75h1q1.75 0 1.75-1.75v-3.25h2.25q1.76 0 3.005-1.245T20.75 13V6q0-1.76-1.245-3.005T16.5 1.75m0 15.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-3-3.75-3t-3.75 3q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146Q6.75 12 12 12t5.25 4.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014m-4.5-12q2.75 0 2.75 2.75T12 10.75T9.25 8T12 5.25m-.75 15.25v-3.25h1.5v3.25q0 .25-.25.25h-1q-.25 0-.25-.25");
}

</style>
