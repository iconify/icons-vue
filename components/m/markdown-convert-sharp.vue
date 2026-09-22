<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zc06z8sin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:markdown-convert-sharp" /></template>
<style>
.zc06z8sin {
  fill: currentColor;
  d: path("M3 19V5h18v3.97q-.892-.74-1.968-1.143q-1.076-.404-2.253-.404h-2v4.25h-1.087V19zm18 0h-4.538v-4.538h1v2.77q1.117-.236 1.842-1.126t.725-2.046q0-1.364-.947-2.308t-2.303-.944v-1q1.767 0 3.009 1.236q1.24 1.235 1.24 2.995q0 1.357-.765 2.43q-.767 1.072-1.967 1.531H21zM5.808 14.692h.884v-4.5h1.616v3h.884v-3h1.616v4.5h.884V9.308H5.808z");
}

</style>
