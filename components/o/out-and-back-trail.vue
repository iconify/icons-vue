<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="so9llktwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:out-and-back-trail" /></template>
<style>
.so9llktwa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.5 8q0-2.75 2.75-2.75q2.345 0 2.69 2h8.81q1.968 0 3.359 1.391T21.5 12t-1.391 3.359t-3.359 1.391h-6.689l1.219 1.22q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163l-2.5-2.5q-.106-.105-.163-.243T7.5 16t.056-.285t.16-.242l.004-.003v-.001l2.5-2.499q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113l-1.219 1.22h6.689Q20 15.25 20 12t-3.25-3.25H7.94q-.345 2-2.69 2Q2.5 10.75 2.5 8");
}

</style>
