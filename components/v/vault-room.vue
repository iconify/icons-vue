<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_q-1o3_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:vault-room" /></template>
<style>
.c_q-1o3_r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 2.25h15.5q1.036 0 1.768.732t.732 1.768v12.5q0 1.036-.732 1.768t-1.768.732H4.25q-2.5 0-2.5-2.5V4.75q0-2.5 2.5-2.5M5.75 11q0 2.589 1.831 4.419Q9.411 17.25 12 17.25t4.419-1.831T18.25 11t-1.831-4.419Q14.589 4.75 12 4.75T7.581 6.581Q5.75 8.411 5.75 11m16.5 10.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-19q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146");
}

</style>
