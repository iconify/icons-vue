<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clkb6obxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:markdown-convert" /></template>
<style>
.clkb6obxu {
  fill: currentColor;
  d: path("M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v2.353q-.892-.738-1.968-1.142t-2.253-.404h-2v4.25h-1.087V19zM21 19h-4.538v-4.538h1v2.77q1.117-.238 1.842-1.122t.725-2.052q0-1.362-.947-2.306t-2.303-.944v-1q1.763 0 3.007 1.233q1.243 1.234 1.243 2.998q0 1.367-.766 2.434q-.767 1.068-1.967 1.527H21zM5.808 14.692h.884v-4.5h1.616v3h.884v-3h1.616v4.5h.884V10q0-.31-.191-.501T11 9.308H6.5q-.31 0-.501.191q-.191.192-.191.501z");
}

</style>
