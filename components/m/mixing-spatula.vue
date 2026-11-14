<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1n8_dk6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mixing-spatula" /></template>
<style>
.m1n8_dk6y {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.27 2.708L13.071 8.75H21.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 5.699-3.053 9.298Q16.268 22.25 12 22.25t-7.197-3.452Q1.75 15.199 1.75 9.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h8.975l2.385-6.554q.025-.07.064-.133q.038-.063.088-.118t.109-.098t.127-.075t.139-.049t.145-.02q.074-.004.147.008q.073.011.142.036q.141.051.251.152t.173.236t.069.284t-.044.289m-4.381 9.846q-3.053-1.111-4.165 1.943l-.171.47q-1.111 3.053 1.943 4.165q3.053 1.111 4.165-1.943l.171-.47q1.111-3.053-1.942-4.165");
}

</style>
