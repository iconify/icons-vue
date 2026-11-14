<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ko2zbzeid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:timing-tower" /></template>
<style>
.ko2zbzeid {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 9.627V8.05q.459.2 1 .2h11.5q1.036 0 1.768-.732t.732-1.768q0-2.5-2.5-2.5H5.75q-.541 0-1 .2V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q4.074 1.75 4 1.75t-.146.014t-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146v19q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-.877q.436.127 1 .127h3.5q1.036 0 1.768-.732t.732-1.768t-.732-1.768t-1.768-.732h-3.5q-.541 0-1 .2V14.3q.459.2 1 .2h7.5q1.036 0 1.768-.732T15.75 12t-.732-1.768T13.25 9.5h-7.5q-.564 0-1 .127");
}

</style>
