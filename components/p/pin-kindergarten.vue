<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7yyzc96u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-kindergarten" /></template>
<style>
.j7yyzc96u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8 2.75h12.5q-.15 0-.287.057q-.138.057-.243.163l-4.281 4.28H3.5q-.149 0-.287.057t-.243.163l4.5-4.5q.105-.106.243-.163T8 2.75m8.75 17.75V8.311l4.28-4.281q.106-.105.163-.243t.057-.287V16q0 .149-.057.287t-.163.243l-4.5 4.5q.106-.105.163-.243t.057-.287m-1.5 0V8.75H3.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q2.75 8.074 2.75 8v12.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014H16q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146M6.5 14.25Q6.5 11 9.75 11T13 14.25T9.75 17.5T6.5 14.25");
}

</style>
