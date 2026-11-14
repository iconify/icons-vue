<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtt1yd1vr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:open" /></template>
<style>
.gtt1yd1vr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 6.5V19q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h14.75q.11 0 .215-.031q.105-.032.197-.092q.091-.06.162-.144t.114-.185l3.25-7.5q.062-.142.062-.298q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-2.25V8.5q0-2.25-2.25-2.25h-5.689L9.53 4.47q-.105-.106-.243-.163T9 4.25H5q-2.25 0-2.25 2.25m4 4.25q-.11 0-.215.031q-.105.032-.197.092q-.091.06-.162.144t-.114.185L4.25 15.383V6.5q0-.75.75-.75h3.689l1.781 1.78q.105.106.243.163T11 7.75h6q.75 0 .75.75v2.25z");
}

</style>
