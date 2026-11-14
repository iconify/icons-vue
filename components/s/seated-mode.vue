<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-njlwx_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:seated-mode" /></template>
<style>
.i-njlwx_f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.5 2.25h-11q-1.346 0-2.298.952T2.25 5.5V7q0 3.25 3.25 3.25h1.146l1.104 5.081V21.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V16h9v5.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-6.25q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T19 14.5H9.104l-.923-4.25H10.5q.149 0 .287-.057t.243-.163l.97-.969l.97.969q.105.106.243.163t.287.057h3q3.25 0 3.25-3.25V5.5q0-3.25-3.25-3.25");
}

</style>
