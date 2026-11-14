<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="writ6ac-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mobility-scooter" /></template>
<style>
.writ6ac-c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 7.757V4.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q4.074 3.75 4 3.75t-.146.014t-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v3.879q-.5.56-.5 1.621q0 2.25 2.25 2.25h4q2.25 0 2.25-2.25T9 7.75H5q-.129 0-.25.007M22 18q0-2.496-1.781-3.212l-.012-.038l-3-8.5q-.038-.109-.109-.202q-.07-.093-.165-.16t-.206-.103t-.227-.035h-3q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h2.469l2.559 7.25H18.5q-3.102 0-3.455 2.75h-5.09Q9.602 14.5 6.5 14.5Q3 14.5 3 18t3.5 3.5q3.102 0 3.455-2.75h5.09q.353 2.75 3.455 2.75q3.5 0 3.5-3.5");
}

</style>
