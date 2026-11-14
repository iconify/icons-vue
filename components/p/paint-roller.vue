<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t2jh1veex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:paint-roller" /></template>
<style>
.t2jh1veex {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.625 1.75h9.75q3.047 0 3.343 2.75H20.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v5.5q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-7.75v1.826q1.5.337 1.5 2.174V20q0 2.25-2.25 2.25T9.75 20v-4.5q0-1.837 1.5-2.174V10.75q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T12 10h7.75V6h-1.032q-.296 2.75-3.343 2.75h-9.75q-1.398 0-2.386-.989q-.989-.988-.989-2.386v-.25q0-1.398.989-2.386q.988-.989 2.386-.989");
}

</style>
