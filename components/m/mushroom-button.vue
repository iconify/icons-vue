<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8fw41bzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mushroom-button" /></template>
<style>
.v8fw41bzx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.959 5.793Q3.25 8.615 3.25 13.5q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h3.75v4.25q0 1.346.952 2.298T11 21.75h2q1.346 0 2.298-.952t.952-2.298v-4.25H20q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-4.885-2.709-7.707Q15.6 3.25 12 3.25T5.959 5.793M9.25 18.5v-4.25h5.5v4.25q0 .725-.513 1.237q-.512.513-1.237.513h-2q-.725 0-1.237-.513q-.513-.512-.513-1.237");
}

</style>
