<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avgzhx9gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:stereo-camera" /></template>
<style>
.avgzhx9gm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 5.75h-2.75V4.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043q-.072-.014-.146-.014h-5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13q-.028.068-.043.141T8.75 4.5v1.25H6q-1.76 0-3.005 1.245T1.75 10v6q0 1.76 1.245 3.005T6 20.25h12q1.76 0 3.005-1.245T22.25 16v-6q0-1.76-1.245-3.005T18 5.75m-4.25 0h-3.5v-.5h3.5zM4.5 13q0-1.347.951-2.299q.952-.952 2.299-.952t2.299.952T11 13q.001 1.346-.951 2.299t-2.299.952t-2.299-.952Q4.5 14.347 4.5 13m8.5 0q0-3.25 3.25-3.25T19.5 13t-3.25 3.25T13 13");
}

</style>
