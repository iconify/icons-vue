<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8m794r0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:movie" /></template>
<style>
.c8m794r0q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12M12 4.5q-2.25 0-2.25 2.25T12 9t2.25-2.25T12 4.5M7 8q-2.25 0-2.25 2.25T7 12.5t2.25-2.25T7 8m7.75 2.25q0 2.25 2.25 2.25t2.25-2.25T17 8t-2.25 2.25m-2.74 1H12q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h.01q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014m-5.26 5q0 2.25 2.25 2.25t2.25-2.25T9 14t-2.25 2.25M15 14q-2.25 0-2.25 2.25T15 18.5t2.25-2.25T15 14");
}

</style>
