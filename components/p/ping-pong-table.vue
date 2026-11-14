<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gb_6kqbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ping-pong-table" /></template>
<style>
.gb_6kqbmc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.78 3.75H7.22q-1.743 0-2.346 1.636L3.727 8.5h16.546l-1.147-3.114Q18.523 3.75 16.78 3.75M20.825 10H3.175l-.511 1.386q-.451 1.224.295 2.294q.514.736 1.291.966V19.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-4.75h12.5v4.75q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-4.854q.777-.23 1.291-.966q.746-1.07.295-2.294z");
}

</style>
