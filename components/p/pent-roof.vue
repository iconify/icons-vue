<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7uwjib9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pent-roof" /></template>
<style>
.w7uwjib9h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.546 7.238L4.137 3.136q-.909-.227-1.648.35T1.75 5v.329q0 1.756 1.704 2.183l.296.074V20.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069q.068.028.141.043t.146.014h15q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-8.826q.683.042 1.261-.41q.739-.577.739-1.514v-.329q0-1.756-1.704-2.183M5.25 19.75V7.961l13.5 3.374v8.415z");
}

</style>
