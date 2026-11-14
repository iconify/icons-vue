<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-sx-z_1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:passport-card" /></template>
<style>
.o-sx-z_1x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17 1.75H6Q3.75 1.75 3.75 4v16q0 2.25 2.25 2.25h11q1.346 0 2.298-.952T20.25 19V5q0-3.25-3.25-3.25M6.75 10q0-2.175 1.538-3.712Q9.825 4.75 12 4.75t3.712 1.538Q17.25 7.825 17.25 10t-1.538 3.712q-1.537 1.537-3.71 1.538H12q-2.175 0-3.712-1.538Q6.75 12.175 6.75 10m8.5 7.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h5q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146");
}

</style>
