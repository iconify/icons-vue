<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbnzlebvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:overview-key-rounded" /></template>
<style>
.fbnzlebvj {
  fill: currentColor;
  d: path("M3.385 18q-.69 0-1.153-.462t-.463-1.153v-8.77q0-.69.463-1.152T3.384 6h8.77q.69 0 1.153.463t.462 1.153v8.769q0 .69-.462 1.153T12.154 18zm13.758-.143Q17 17.714 17 17.5v-11q0-.213.143-.357T17.5 6t.357.143T18 6.5v11q0 .214-.143.357T17.5 18t-.357-.143m4.231 0q-.143-.143-.143-.357v-11q0-.213.143-.357T21.731 6t.356.143t.144.357v11q0 .214-.144.357t-.356.143t-.357-.143");
}

</style>
