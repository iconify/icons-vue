<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9syco2ic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:parking-guidance-sign" /></template>
<style>
.i9syco2ic {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.339 2.25H5.125q-1.398 0-2.386.989q-.989.988-.989 2.386v5.75q0 3.375 3.375 3.375h.125v6.75q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-6.75h8.589q1.493 0 2.497-1.104l2.614-2.875q2.065-2.271 0-4.542l-2.614-2.875Q16.832 2.25 15.339 2.25m-5.589 8.5v.5q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043T9 12t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146V6q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T9 5.25h2.5q2.75 0 2.75 2.75t-2.75 2.75zm0-1.5h1.75q1.25 0 1.25-1.25T11.5 6.75H9.75z");
}

</style>
