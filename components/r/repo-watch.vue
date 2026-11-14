<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j969o_r-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:repo-watch" /></template>
<style>
.j969o_r-n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m7.683 3.439l10.02 2.672q3.203.855 2.4 4.071q-.334 1.335-1.52 2.034t-2.516.345L12 11.476V16q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-6.5v3.75q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T4 21.25t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-8q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T4 11.75t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v2.75h5.75v-4.174L6.047 9.889q-3.203-.855-2.4-4.071q.334-1.335 1.52-2.034t2.516-.345M15.5 7q-2 0-2 2t2 2t2-2t-2-2");
}

</style>
