<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="undgqdd3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:temperature-gauge-device" /></template>
<style>
.undgqdd3u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.75 13.634Q7.238 14.9 7.027 16.916q-.232 2.214 1.258 3.867T12 22.437t3.715-1.654q1.49-1.653 1.258-3.867q-.211-2.016-1.723-3.282V5.5q0-3.25-3.25-3.25T8.75 5.5zm4 2.366q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T11.25 16V8q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T12 7.25t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146z");
}

</style>
