<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="maf9y3bpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:map-boss-marker" /></template>
<style>
.maf9y3bpe {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 10q0 4.311 7.72 12.03q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q7.72-7.719 7.72-12.03q0-3.417-2.416-5.834T12 1.75T6.166 4.166Q3.75 6.583 3.75 10m3.5 0q0-1.968 1.391-3.359T12 5.25t3.359 1.391T16.75 10v2.75q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043T16 13.5h-1V15q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-4.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T9 15v-1.5H8q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146z");
}

</style>
