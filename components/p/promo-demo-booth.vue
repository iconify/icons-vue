<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hx21dibno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:promo-demo-booth" /></template>
<style>
.hx21dibno {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.25 13.25q0-2.5 2.5-2.5h6.5q2.5 0 2.5 2.5v2q0 .564-.127 1H20.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v4q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-17q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.75 21v-4q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h2.877q-.127-.436-.127-1zM2.311 6.205q-.061.141-.061.295q.001 2.999 3 2.999q1.499 0 2.249-.75q.75.751 2.251.751T12 8.75q.75.75 2.25.75t2.251-.751q.75.749 2.249.749q2.998 0 3-2.997v-.022z");
}

</style>
