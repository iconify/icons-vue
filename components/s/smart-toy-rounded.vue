<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sktmkfbje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:smart-toy-rounded" /></template>
<style>
.sktmkfbje {
  fill: currentColor;
  d: path("M5 14q-.846 0-1.423-.577T3 12t.577-1.423T5 10V7q0-.397.302-.699T6 6h4q0-.846.577-1.423T12 4t1.423.577T14 6h4q.397 0 .699.302T19 7v3q.846 0 1.423.577T21 12t-.577 1.423T19 14v5q0 .397-.302.699T18 20H6q-.397 0-.699-.302T5 19zm4.707-1.791q.293-.291.293-.707t-.291-.709t-.707-.293t-.709.291t-.293.707t.291.709t.707.293t.709-.291m6 0q.293-.291.293-.707t-.291-.709t-.707-.293t-.709.291t-.293.707t.291.709t.707.293t.709-.291M9 16.5h6q.213 0 .356-.144t.144-.357t-.144-.356T15 15.5H9q-.213 0-.356.144t-.144.357t.144.356T9 16.5");
}

</style>
