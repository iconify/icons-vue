<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5yuldx2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tyre-pressure-gauge" /></template>
<style>
.j5yuldx2k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.52 4.02Q3.25 6.29 3.25 9.5t2.27 5.48q2 2 4.73 2.238V18q0 2.75 2.75 2.75h2.326q.337 1.5 2.174 1.5H19q2.25 0 2.25-2.25T19 17.75h-1.5q-1.837 0-2.174 1.5H13q-1.25 0-1.25-1.25v-.782q2.73-.238 4.73-2.238q2.27-2.27 2.27-5.48t-2.27-5.48T11 1.75T5.52 4.02m7.7 2.2q.105-.106.243-.163T13.75 6t.287.057t.243.163q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113l-2.75 2.75q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113z");
}

</style>
