<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="db4uihm7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:video-off" /></template>
<style>
.db4uihm7m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.03 2.97l17 17q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-17-17q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.75 3.5t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094m16.965 13.151q-.873.502-1.744.301L8.078 5.25h3.047q2.123 0 3.624 1.501q1.09 1.091 1.389 2.509l2.352-1.373q1.25-.729 2.505-.008t1.255 2.168v3.906q0 1.447-1.255 2.168m-9.87 2.629q2.006 0 3.456-1.34L3.601 6.429q-.179.151-.35.322Q1.75 8.252 1.75 10.375v3.25q0 2.123 1.501 3.624t3.624 1.501z");
}

</style>
