<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wphaehb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mortgage-stamp-duty" /></template>
<style>
.wphaehb4k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.25 5v2.25h-2.5q-2.5 0-2.5 2.5t2.5 2.5h10.5q2.5 0 2.5-2.5t-2.5-2.5h-2.5V5q0-2.75-2.75-2.75T9.25 5m1.5 0v2.25h2.5V5q0-1.25-1.25-1.25T10.75 5m7.5 8.75q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T17.5 13h-11q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h11q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146m-10.1 4.2l2.5-1.875q1.35-1.012 2.7 0l2.5 1.875q.9.675.9 1.8v.5q0 2-2 2h-5.5q-2 0-2-2v-.5q0-1.125.9-1.8");
}

</style>
