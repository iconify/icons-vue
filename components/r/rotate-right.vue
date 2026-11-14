<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emfikvbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:rotate-right" /></template>
<style>
.emfikvbdr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m14.03 2.47l3.5 3.5q.106.105.163.243t.057.287t-.057.287t-.163.243l-3.5 3.5q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T12.75 10t.014-.146q.015-.073.043-.141t.069-.13t.094-.113l2.085-2.086q-4.043.573-7.071 3.6Q4.25 14.719 4.25 20q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.75 20q0-5.903 4.174-10.076q3.552-3.553 8.358-4.082L12.97 3.53q-.053-.052-.094-.113t-.069-.13t-.043-.141T12.75 3t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.105-.106.243-.163t.287-.057t.287.057t.243.163");
}

</style>
