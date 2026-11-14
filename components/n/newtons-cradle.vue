<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tm2y60jrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:newtons-cradle" /></template>
<style>
.tm2y60jrk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.5 2.75H17q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043T17 4.25h-1.25l3.089 5.791q.31-.041.661-.041q3 0 3 3t-3 3t-3-3q0-1.671.931-2.411L14.05 4.25h-3.3v10.304Q13 14.902 13 17.5q0 3-3 3q-1.5 0-2.25-.75q-.75.75-2.25.75q-3 0-3-3q0-2.598 2.25-2.946V4.25H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q1.75 3.574 1.75 3.5t.014-.146t.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014m6.75 11.804q-.951.147-1.5.696q-.549-.549-1.5-.696V4.25h3z");
}

</style>
