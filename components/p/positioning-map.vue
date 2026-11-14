<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcg182bvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:positioning-map" /></template>
<style>
.qcg182bvj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 3.5v16.25H20.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-17q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-17q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146m10.5 3q0-1.75 1.75-1.75t1.75 1.75t-1.75 1.75t-1.75-1.75M9 6.75q-1.75 0-1.75 1.75T9 10.25t1.75-1.75T9 6.75m2.5 5.5q-1.75 0-1.75 1.75t1.75 1.75T13.25 14t-1.75-1.75M15.75 15q0-1.75 1.75-1.75T19.25 15t-1.75 1.75T15.75 15");
}

</style>
