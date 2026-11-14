<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sk3au4g9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:shoe-store" /></template>
<style>
.sk3au4g9c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.311 6.205q-.061.141-.061.295q.001 2.999 3 2.999q1.499 0 2.249-.75q.75.751 2.251.751T12 8.75q.75.75 2.25.75t2.251-.751q.75.749 2.249.749q2.998 0 3-2.997v-.022zM7 9.75q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v11q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h12.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V20q0-.389-.046-.741q.046-.125.046-.259q0-.151-.058-.29t-.166-.245q-.526-1.589-2.289-2.177l-.021-.006l-4.466-1.34V10.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014z");
}

</style>
