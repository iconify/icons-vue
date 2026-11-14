<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nj1lgowyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:vector" /></template>
<style>
.nj1lgowyj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.491 17.57q.259.585.259 1.43q0 2.75-2.75 2.75T2.25 19T5 16.25q.845 0 1.43.259L18.189 4.75H11.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T10.75 4t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014H20q.149 0 .287.057t.243.163q.106.105.163.243T20.75 4v8.5q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146V5.811z");
}

</style>
