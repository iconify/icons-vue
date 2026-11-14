<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3zf_ac9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:poison-bottle" /></template>
<style>
.y3zf_ac9c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14 1.75h-4q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v2.949q-5 1.698-5 7.051V19q0 1.346.952 2.298t2.298.952h9q3.25 0 3.25-3.25v-6.5q0-5.353-5-7.051V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q14.074 1.75 14 1.75M7.25 13.5q0-1.968 1.391-3.359T12 8.75t3.359 1.391T16.75 13.5V16q0 1.75-1.75 1.75h-.25v.75q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-4q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-.75H9q-1.75 0-1.75-1.75z");
}

</style>
