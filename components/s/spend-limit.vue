<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0u0xcchk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:spend-limit" /></template>
<style>
.y0u0xcchk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.5 3.25h-19q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141Q1.75 3.926 1.75 4t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T22.25 4t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014M6 7.25h12q1.76 0 3.005 1.245T22.25 11.5v4q0 1.76-1.245 3.005T18 19.75H6q-1.76 0-3.005-1.245T1.75 15.5v-4q0-1.76 1.245-3.005T6 7.25m2.5 6.25Q8.5 17 12 17t3.5-3.5T12 10t-3.5 3.5");
}

</style>
