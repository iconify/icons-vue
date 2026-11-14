<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7-jxj-7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pinball-flipper" /></template>
<style>
.k7-jxj-7q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.75 4q-3.5 0-3.5 3.5q0 2.462 1.732 3.192L4.46 13.308q-1.738.645-2.366 2.396q-.635 1.769.321 3.386t2.811 1.915q1.848.296 3.258-.932l12.191-9.952q1.703-.986.731-2.735q-.41-.738-1.221-.97q-.799-.228-1.526.166L15.18 8.23q.07-.351.07-.73q0-1.45-1.025-2.475T11.75 4M6.01 16.25q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H6q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T5.25 17q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T6 16.25z");
}

</style>
