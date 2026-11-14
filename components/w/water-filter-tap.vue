<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6vgfbbkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:water-filter-tap" /></template>
<style>
.b6vgfbbkj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 22.25H4q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T4 20.75h2.25V8q0-2.382 1.684-4.066T12 2.25t4.066 1.684T17.75 8v.799q2.5.351 2.5 3.201v1.5q0 3.25-3.25 3.25t-3.25-3.25V12q0-2.85 2.5-3.201V8q0-1.76-1.245-3.005T12 3.75T8.995 4.995T7.75 8v12.75H10q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014");
}

</style>
