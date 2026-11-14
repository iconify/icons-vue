<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ori33zb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sensitivity-analysis" /></template>
<style>
.ori33zb_m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 2v1.25H19q1.25 0 1.25 1.25T19 5.75h-6.25v2h6.75q1.25 0 1.25 1.25t-1.25 1.25h-6.75v2h2.75q1.25 0 1.25 1.25t-1.25 1.25h-2.75v2H14q1.25 0 1.25 1.25T14 19.25h-1.25V22q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T11.25 22v-2.75H10q-1.25 0-1.25-1.25T10 16.75h1.25v-2H7.5q-1.25 0-1.25-1.25t1.25-1.25h3.75v-2H5q-1.25 0-1.25-1.25T5 7.75h6.25v-2H3q-1.25 0-1.25-1.25T3 3.25h8.25V2q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146");
}

</style>
