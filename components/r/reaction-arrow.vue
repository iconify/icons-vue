<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zygpfmmau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:reaction-arrow" /></template>
<style>
.zygpfmmau {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m16.03 5.47l6 6q.106.105.163.243t.057.287t-.057.287t-.163.243l-6 6q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141T14.75 18t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113l4.719-4.72H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q1.75 12.074 1.75 12t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h17.189L14.97 6.53q-.053-.052-.094-.113t-.069-.13t-.043-.141T14.75 6t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094");
}

</style>
