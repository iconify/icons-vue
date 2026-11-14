<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="il10fgbdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:salon-chair" /></template>
<style>
.il10fgbdx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16 1.75q2.75 0 2.75 2.75V10q0 1.189-.514 1.863q.514.562.514 1.637q0 2.25-2.25 2.25h-4.25v3.015q4.5.189 4.5 2.735q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H7q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-2.546 4.5-2.735V15.75H6.5q-2.25 0-2.25-2.25t2.25-2.25h6.938q-.188-.531-.188-1.25V4.5q0-2.75 2.75-2.75");
}

</style>
