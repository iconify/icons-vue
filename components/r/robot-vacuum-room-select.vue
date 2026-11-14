<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o69-nwbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:robot-vacuum-room-select" /></template>
<style>
.o69-nwbqg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 19.75h8.672l-.336-.336q-.236-.235-.382-.534t-.188-.63H10.25V5.75H19q1.25 0 1.25 1.25v6.896q.179-.072.368-.109T21 13.75t.382.037t.368.109V7q0-2.75-2.75-2.75H5Q2.25 4.25 2.25 7v10q0 2.75 2.75 2.75m10.28-2.28l1.47 1.469l3.72-3.719q.052-.053.113-.094t.13-.069t.141-.043T21 15t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.106.105.163.243t.057.287t-.057.287t-.163.243l-4.25 4.25q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-2-2q-.053-.052-.094-.113t-.069-.13t-.043-.141T14 18t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.105-.106.243-.163t.287-.057t.287.057t.243.163m4.642 2.186q1.414-.32 1.734-1.734z");
}

</style>
