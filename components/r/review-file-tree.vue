<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="onvb7-b2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:review-file-tree" /></template>
<style>
.onvb7-b2e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 6q0-2.75 2.75-2.75h4.5q.149 0 .287.057t.243.163l1.781 1.78H19q2.75 0 2.75 2.75v10q0 2.75-2.75 2.75H5q-2.75 0-2.75-2.75zm5.5 5.75h2.076q.337 1.5 2.174 1.5q2.25 0 2.25-2.25T12 8.75q-1.837 0-2.174 1.5H7.75v-1.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T7 8t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v7q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043T7 16.5h6.826Q14.163 18 16 18q2.25 0 2.25-2.25T16 13.5q-1.837 0-2.174 1.5H7.75z");
}

</style>
