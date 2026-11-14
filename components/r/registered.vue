<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zohno3b1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:registered" /></template>
<style>
.zohno3b1x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12m7 4.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-3.25h1.834l2.28 3.647q.039.063.09.117t.111.097t.127.073t.139.047q.072.016.146.019t.147-.01q.073-.012.142-.039q.069-.026.131-.065q.063-.039.117-.09t.097-.111t.073-.127t.047-.139t.019-.146t-.01-.147t-.039-.142t-.065-.131l-1.845-2.953Q16 12.68 16 10q0-3.25-3.25-3.25H9.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146zm3.75-4.75h.25q1.75 0 1.75-1.75t-1.75-1.75h-2.5v3.5z");
}

</style>
