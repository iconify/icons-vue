<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfh8n5bom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:signal-cellular-connected-no-internet-4-bar-outline-rounded" /></template>
<style>
.tfh8n5bom {
  fill: currentColor;
  d: path("M4.373 19.627L19.602 4.398q.385-.384.891-.177t.507.742v2.268h-.5q-1.202 0-2.043.841q-.842.842-.842 2.044V21H4.94q-.535 0-.74-.497t.174-.876m15.607 1.394q-.21-.21-.21-.52t.21-.521q.209-.21.52-.21t.52.21q.21.209.21.52t-.21.52q-.209.21-.52.21t-.52-.21m.02-3.75v-7.154q0-.213.144-.357t.357-.143t.356.143t.143.357v7.178q0 .195-.144.335t-.357.14t-.356-.143t-.143-.357");
}

</style>
