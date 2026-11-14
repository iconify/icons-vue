<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dc1vd8j4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sight-reading" /></template>
<style>
.dc1vd8j4e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 1.75q-2.75 0-2.75 2.75v15q0 2.75 2.75 2.75h10q2.75 0 2.75-2.75V7q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T19 7.75h-4.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T13.75 7V2.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014zm8.031.22q.105.106.162.243q.057.138.057.287v3.75H19q.149 0 .287.057t.243.163zM13.75 16q0 1.115-1.052 1.852q-.926.648-2.198.648q-3.25 0-3.25-2.5t3.25-2.5q.977 0 1.75.382V9.75q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T13 9t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146z");
}

</style>
