<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmd_s6pcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sidebar-right" /></template>
<style>
.vmd_s6pcz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15 3.25H7.75q-2.485 0-4.243 1.757Q1.75 6.765 1.75 9.25v5.5q0 2.485 1.757 4.243Q5.265 20.75 7.75 20.75h8.5q2.485 0 4.243-1.757q1.757-1.758 1.757-4.243v-5.5q0-2.485-1.757-4.243Q18.735 3.25 16.25 3.25zm0 0q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v16q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T14.25 20V4q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014");
}

</style>
