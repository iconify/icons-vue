<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0_bsibmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:scuba-mask" /></template>
<style>
.c0_bsibmf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 5.25Q2.75 5.25 2.75 9v4q0 1.553 1.098 2.652Q4.947 16.75 6.5 16.75h3q.149 0 .287-.057t.243-.163L12 14.561l1.97 1.969q.105.106.243.163t.287.057h3q3.75 0 3.75-3.75V9q0-3.75-3.75-3.75zm5.5 0q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v4.5q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146V6q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T12 5.25");
}

</style>
