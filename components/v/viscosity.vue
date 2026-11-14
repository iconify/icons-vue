<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyd89zb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:viscosity" /></template>
<style>
.qyd89zb5t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.5 3.25h16.75q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141T20 4q0 2.444.869 6.366q.631 2.845.631 4.134q0 3-3 3t-3-3q0-1.289.631-4.134q.741-3.346.85-5.616H14.25V18q0 3.25-3.25 3.25H6q-3.25 0-3.25-3.25V4.75H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q1.75 4.074 1.75 4t.014-.146t.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014m15.983 1.5q-.108 2.423-.888 5.941Q17 13.376 17 14.5q0 1.5 1.5 1.5t1.5-1.5q0-1.124-.595-3.809q-.78-3.518-.888-5.941zm-5.733 0h-8.5V18q0 1.75 1.75 1.75h5q1.75 0 1.75-1.75z");
}

</style>
