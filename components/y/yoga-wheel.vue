<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oswzv-bfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:yoga-wheel" /></template>
<style>
.oswzv-bfl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 10.5q-.001-3.832 2.708-6.543q2.71-2.71 6.542-2.71t6.542 2.71q2.709 2.711 2.708 6.543q.001 3.832-2.708 6.543q-2.71 2.71-6.542 2.71t-6.542-2.71T2.75 10.5m19 11.25q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 21H3q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043T3 22.5h18q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146");
}

</style>
