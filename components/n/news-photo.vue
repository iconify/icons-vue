<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nt9svdbfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:news-photo" /></template>
<style>
.nt9svdbfe {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.5 1.75h-9q-1.76 0-3.005 1.245T3.25 6v12q0 1.76 1.245 3.005T7.5 22.25h9q1.76 0 3.005-1.245T20.75 18V6q0-1.76-1.245-3.005T16.5 1.75m-7.75 3h6.5q2.5 0 2.5 2.5v5q0 2.5-2.5 2.5h-6.5q-2.5 0-2.5-2.5v-5q0-2.5 2.5-2.5m8.25 12q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H7q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T7 16.75z");
}

</style>
