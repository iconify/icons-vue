<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uu_lktojl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:potted-plant-small" /></template>
<style>
.uu_lktojl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.736 6.095Q10.134 3.75 6 3.75q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 5.893 6 6.23v2.02H6.5q-.07 0-.138.013q-.147.027-.272.109q-.125.081-.209.204q-.084.124-.115.27t-.003.292l1.5 8q.012.064.035.125t.056.117t.075.106t.092.091q.05.042.107.074t.117.054q.062.023.126.034T8 22.25h8q.065 0 .129-.011t.126-.034q.061-.022.117-.054t.107-.074t.092-.091t.075-.106t.056-.117q.023-.061.035-.125l1.5-8q.013-.068.013-.138q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-4.75V9.73q6-.337 6-6.23q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T18 2.75q-4.938 0-6.264 3.345");
}

</style>
