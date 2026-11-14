<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdx-r-dtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tampons-box" /></template>
<style>
.zdx-r-dtc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.375 1.75h-8.75q-3.375 0-3.375 3.375v13.75q0 3.375 3.375 3.375h8.75q3.375 0 3.375-3.375V5.125q0-3.375-3.375-3.375M19.75 6.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T19 5.75H5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043T5 7.25h4.826q.337 1.5 2.174 1.5t2.174-1.5H19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146M7 15.25v-2q0-2.5 2.5-2.5h5q1.036 0 1.768.732T17 13.25v2q0 1.036-.732 1.768t-1.768.732h-5q-2.5 0-2.5-2.5");
}

</style>
