<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izuf8ubeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:phone-camera-module" /></template>
<style>
.izuf8ubeq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.75 1.75h-3.5q-2.485 0-4.243 1.757Q4.25 5.265 4.25 7.75v8.5q0 2.485 1.757 4.243q1.758 1.757 4.243 1.757h3.5q2.485 0 4.243-1.757q1.757-1.758 1.757-4.243v-8.5q0-2.485-1.757-4.243Q16.235 1.75 13.75 1.75M7.5 7.5Q7.5 5 10 5t2.5 2.5T10 10T7.5 7.5m7.01-.75q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-.01q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014zM10 11.25q2.5 0 2.5 2.5t-2.5 2.5t-2.5-2.5t2.5-2.5");
}

</style>
