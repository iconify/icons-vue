<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjqe43nen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tooltip" /></template>
<style>
.yjqe43nen {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.5 3.25h-15q-1.139 0-1.945.805Q1.75 4.861 1.75 6v8.5q0 2.75 2.75 2.75h4.649l2.275 2.73q.043.053.096.096q.057.047.121.083q.065.035.136.057q.07.022.144.03t.147.001t.144-.028t.137-.055q.065-.034.122-.081q.058-.046.105-.103l2.275-2.73H19.5q2.75 0 2.75-2.75V6q0-2.75-2.75-2.75M17 9.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043T17 11H7q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T7 9.5z");
}

</style>
