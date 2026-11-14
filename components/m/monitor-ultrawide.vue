<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igifol5qn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:monitor-ultrawide" /></template>
<style>
.igifol5qn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.938 5.25h12.125q1.942 0 3.314 1.374q1.373 1.373 1.373 3.314v1.625q0 1.941-1.373 3.314t-3.314 1.373H12.75v2h2.75q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-7q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T7.75 19q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h2.75v-2H5.938q-1.941 0-3.314-1.373q-1.374-1.372-1.374-3.314V9.938q0-1.942 1.373-3.315T5.938 5.25");
}

</style>
