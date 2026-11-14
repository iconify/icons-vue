<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bf2vdmbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:soccer-centre-circle" /></template>
<style>
.bf2vdmbid {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 3.75H5.125q-3.375 0-3.375 3.375v9.75q0 3.375 3.375 3.375h13.75q3.375 0 3.375-3.375v-9.75q0-3.375-3.375-3.375zm0 0q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v2.298q1.697.224 2.962 1.49Q17.25 9.825 17.25 12t-1.538 3.712q-1.265 1.266-2.962 1.49V19.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-2.298q-1.697-.224-2.962-1.49Q6.75 14.175 6.75 12t1.538-3.712q1.265-1.266 2.962-1.49V4.5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014");
}

</style>
