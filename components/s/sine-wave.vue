<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqzo3zqns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sine-wave" /></template>
<style>
.lqzo3zqns {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.499 12.75H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q1.75 12.074 1.75 12t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h.443Q4.93 4.875 7.75 4.875t4.807 6.375H21.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-.443q-1.987 6.375-4.807 6.375t-4.807-6.375zm1.017-1.5h6.468Q9.408 6.375 7.75 6.375T4.516 11.25m8.5 1.5q1.576 4.875 3.234 4.875t3.234-4.875z");
}

</style>
