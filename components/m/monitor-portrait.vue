<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3_l-33fz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:monitor-portrait" /></template>
<style>
.i3_l-33fz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.5 1.75h5q1.76 0 3.005 1.245T18.75 6v8q0 1.76-1.245 3.005T14.5 18.25h-1.75v2H16q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H8q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T7.25 21q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T8 20.25h3.25v-2H9.5q-1.76 0-3.005-1.245T5.25 14V6q0-1.76 1.245-3.005T9.5 1.75");
}

</style>
