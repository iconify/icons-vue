<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uo1cadlnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:prohibited-items" /></template>
<style>
.uo1cadlnk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12m14.793 3.482q.207-.512.207-1.232v-3.5q0-2.5-2.5-2.5h-4.5q-.22 0-.42.019L6.03 4.97q-.052-.053-.113-.094t-.13-.069t-.141-.043T5.5 4.75t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113l2.875 2.876q-.595.624-.595 1.844v3.5q0 2.5 2.5 2.5h4.5q.72 0 1.232-.207l2.488 2.487q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113z");
}

</style>
