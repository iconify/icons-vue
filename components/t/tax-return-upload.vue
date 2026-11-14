<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrr3y3b3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tax-return-upload" /></template>
<style>
.jrr3y3b3l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.469 1.97L8.22 5.22q-.053.052-.094.113t-.069.13t-.043.141T8 5.75t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.105.106.243.163t.287.057t.287-.057t.243-.163l1.97-1.969V9.75q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V4.311l1.97 1.969q.105.106.243.163t.287.057t.287-.057t.243-.163q.053-.052.094-.113t.069-.13t.043-.141T16 5.75t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-3.249-3.25h-.001q-.105-.106-.243-.163T12 1.75t-.287.057t-.243.163zm3.031 9.78q.149 0 .287.057t.243.163l3.5 3.5q.106.105.163.243t.057.287v3.5q0 2.75-2.75 2.75H8q-2.75 0-2.75-2.75v-5q0-2.75 2.75-2.75z");
}

</style>
