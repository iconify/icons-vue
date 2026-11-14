<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2fhwmb2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:platform-bed" /></template>
<style>
.c2fhwmb2i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 13.25V5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T3 4.25t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141Q2.25 4.926 2.25 5v14.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h18q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V14q0-.09-.021-.178t-.063-.168t-.101-.148t-.134-.119q.319-.659.319-1.637q0-3-3-3H8.25q-1.243 0-2.121.879q-.879.878-.879 2.121q0 .879.257 1.5zm15 1.5h1.5v4H3.75v-4z");
}

</style>
