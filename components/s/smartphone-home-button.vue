<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1d82ib9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:smartphone-home-button" /></template>
<style>
.w1d82ib9l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.375 1.75h3.25q2.123 0 3.624 1.501t1.501 3.624v10.25q0 2.123-1.501 3.624t-3.624 1.501h-3.25q-2.123 0-3.624-1.501T5.25 17.125V6.875q0-2.123 1.501-3.624t3.624-1.501M10.5 4.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043T10.5 6h3q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T13.5 4.5zm-.75 13q0 2.25 2.25 2.25t2.25-2.25T12 15.25T9.75 17.5");
}

</style>
