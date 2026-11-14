<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6b99bcgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:potted-cactus" /></template>
<style>
.y6b99bcgy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.259 13.75H14.75v-3.5h.75q2.25 0 2.25-2.25V5.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T17 4.75q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146V8q0 .75-.75.75h-.75V5q0-2.75-2.75-2.75T9.25 5v5.75H8.5q-.75 0-.75-.75V7q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T7 6.25t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T6.25 7v3q0 2.25 2.25 2.25h.75v1.5H7.741q-1.22.001-1.97.962t-.455 2.144l.875 3.5q.473 1.893 2.425 1.894h6.768q1.952-.001 2.425-1.894l.875-3.5q.295-1.183-.455-2.144t-1.97-.962M13.25 9.5v4.25h-2.5V5q0-1.25 1.25-1.25T13.25 5z");
}

</style>
