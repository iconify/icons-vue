<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbm88pb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tree-canopy" /></template>
<style>
.fbm88pb_u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.925 16.746q-3.494-.351-4.183-3.794q-.64-3.199 1.982-4.866q-.11-3.63 3.307-5.238q3.382-1.591 6.088.741q1.807-.855 3.806-.336q2.277.59 3.469 2.618q1.193 2.027.603 4.305q-.539 2.082-2.281 3.259q-.272 2.239-2.395 3.243q-.153.072-.321.072h-4.25v4.75q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-2.189L8.689 16.75H7q-.038 0-.075-.004m3.886.004l.439.439v-.439z");
}

</style>
