<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vd6d48bfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:remit-home-delivery" /></template>
<style>
.vd6d48bfd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.875 3.75h-3.75q-3.375 0-3.375 3.375v2.75q0 3.375 3.375 3.375h3.75q3.375 0 3.375-3.375v-2.75q0-3.375-3.375-3.375M4.25 8.5q0-2.75 2.75-2.75T9.75 8.5T7 11.25T4.25 8.5m12.734 6.214q-1.685.553-1.939 2.536h-6.09Q8.602 14.5 5.5 14.5Q2 14.5 2 18t3.5 3.5q3.102 0 3.455-2.75h6.09q.353 2.75 3.455 2.75q3.5 0 3.5-3.5t-3.5-3.5h-.026L16.94 7.75h.81q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T18.5 7t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-3.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T13.5 7t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h1.151z");
}

</style>
