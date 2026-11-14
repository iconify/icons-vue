<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="arygccc4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:purchase-order-confirmed" /></template>
<style>
.arygccc4q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 1.75h6.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v4q0 2.615 2.488 2.743l-4.288 5.146l-2.42-2.419q-.052-.053-.113-.094t-.13-.069t-.141-.043T8 11.75t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.106.105-.163.243t-.057.287t.057.287t.163.243l3 3q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.024-.024.046-.05l5-6q.063-.075.104-.163t.058-.185t.01-.193q-.008-.097-.041-.189H19.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V19q0 1.346-.952 2.298T17 22.25H7q-1.346 0-2.298-.952T3.75 19V5q0-1.346.952-2.298T7 1.75m7.25.75q0-.149-.057-.287t-.162-.243l5.999 6q-.105-.106-.243-.163T19.5 7.75h-4q-1.25 0-1.25-1.25z");
}

</style>
