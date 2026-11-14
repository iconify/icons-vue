<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6ve9gb-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-dry-cleaner" /></template>
<style>
.h6ve9gb-x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 6.75q0-3 3-3t3 3q0 2.598-2.25 2.946v.435l8.458 6.525q.112.087.185.208q.607 1.011.188 1.709q-.406.677-1.581.677H4q-1.175 0-1.581-.677q-.419-.698.188-1.709q.073-.121.185-.208l8.458-6.525V9q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T12 8.25q1.5 0 1.5-1.5T12 5.25t-1.5 1.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T9 6.75");
}

</style>
