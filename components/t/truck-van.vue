<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-ff54bhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:truck-van" /></template>
<style>
.g-ff54bhy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 17V8q0-2.75 2.75-2.75h9q.149 0 .287.057t.243.163l4.781 4.78H21q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v6q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-1.81q.06.345.06.75q0 2.75-2.75 2.75t-2.75-2.75q0-.405.06-.75h-3.62q.06.345.06.75q0 2.75-2.75 2.75T4.75 18.5q0-.405.06-.75H3q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.25 17");
}

</style>
