<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gyboxbyee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:parking-permit" /></template>
<style>
.gyboxbyee {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.25 4.25v2H8.5q-1.76 0-3.005 1.245T4.25 10.5V18q0 1.76 1.245 3.005T8.5 22.25h7q1.76 0 3.005-1.245T19.75 18v-7.5q0-1.76-1.245-3.005T15.5 6.25h-2.75v-2q0-1 1-1q.414 0 .707.293t.293.707q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043T15.5 5q.149 0 .287-.057t.243-.163q.106-.105.163-.243t.057-.287q0-1.036-.732-1.768T13.75 1.75q-2.5 0-2.5 2.5M9.25 15v-5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T10 9.25h3q3.25 0 3.25 3.25T13 15.75h-2.25v2.75q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146zm1.5-.75H13q1.75 0 1.75-1.75T13 10.75h-2.25z");
}

</style>
