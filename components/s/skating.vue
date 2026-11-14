<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9re1fbxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:skating" /></template>
<style>
.l9re1fbxe {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 15.5v-11q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q4.926 3.75 5 3.75h6q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v3.975l4.997 1.817q4.003 1.339 4.003 5.208q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146m3.25.75q2.75 0 2.75 2.75T7.5 21.75T4.75 19t2.75-2.75m9.5 0q2.75 0 2.75 2.75T17 21.75T14.25 19T17 16.25");
}

</style>
