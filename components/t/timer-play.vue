<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apygjjbav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:timer-play" /></template>
<style>
.apygjjbav {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.5 1.75h-5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043q.072.014.146.014h5q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043q-.072-.014-.146-.014M3.25 13q0-3.624 2.563-6.187T12 4.25t6.187 2.563T20.75 13t-2.563 6.187T12 21.75t-6.187-2.563T3.25 13m9.685-2.47q-1.125-.696-2.28-.052q-1.156.644-1.155 1.966v1.114q-.001 1.322 1.155 1.966t2.28-.053l.9-.558Q14.9 14.253 14.9 13t-1.065-1.912z");
}

</style>
