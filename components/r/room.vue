<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="glt_64b0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:room" /></template>
<style>
.glt_64b0x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 21.75H5q-2.75 0-2.75-2.75V5q0-2.75 2.75-2.75h14q2.75 0 2.75 2.75v14q0 2.75-2.75 2.75h-4q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T14.25 21v-5.202q-1.697.224-2.962 1.49Q9.75 18.825 9.75 21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T9 21.75m-.713-1.5H5q-1.25 0-1.25-1.25V5q0-1.25 1.25-1.25h14q1.25 0 1.25 1.25v14q0 1.25-1.25 1.25h-3.25V15q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T15 14.25q-2.796 0-4.773 1.977q-1.706 1.706-1.94 4.023");
}

</style>
