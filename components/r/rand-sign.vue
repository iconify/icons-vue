<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkhsnh97s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:rand-sign" /></template>
<style>
.nkhsnh97s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.25 20V4q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q6.926 3.25 7 3.25h5.5q2.071 0 3.536 1.464Q17.5 6.179 17.5 8.25t-1.464 3.536q-1.297 1.296-3.07 1.445l4.639 6.325q.043.06.075.127q.031.067.048.139q.018.071.021.145t-.008.147t-.036.142q-.025.07-.064.133q-.038.063-.088.118t-.109.098t-.127.075q-.067.031-.139.048q-.071.018-.145.021t-.147-.008t-.142-.036q-.07-.025-.133-.064q-.063-.038-.118-.088t-.098-.109L11.12 13.25H7.75V20q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T7 20.75t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T6.25 20m5.25-8.25h1q3.5 0 3.5-3.5t-3.5-3.5H7.75v7z");
}

</style>
