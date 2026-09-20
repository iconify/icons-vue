<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wighoeb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:volcano-rounded" /></template>
<style>
.wighoeb8d {
  fill: currentColor;
  d: path("M18.542 21H6.017q-.869 0-1.35-.727t-.11-1.535l1.668-3.769q.212-.453.603-.711T7.704 14h1.969l1.596-3.98q.187-.46.59-.74q.405-.28.914-.28h3.266q.54 0 .969.323t.57.858l2.505 8.769q.217.777-.258 1.414T18.542 21M13.884 4.77v-2q0-.214.144-.358q.143-.143.357-.143q.213 0 .356.143t.144.357v2q0 .214-.144.357t-.356.143t-.357-.143t-.144-.357m3.672 1.121L19 4.466q.14-.14.341-.14t.347.14q.166.146.166.354t-.166.354l-1.444 1.425q-.14.14-.341.134t-.347-.153q-.14-.14-.14-.345q0-.203.14-.344m-7.031.689L9.081 5.154q-.14-.14-.14-.342t.14-.347q.146-.165.354-.165q.207 0 .353.166l1.425 1.443q.14.141.144.332t-.143.338q-.141.14-.345.14t-.344-.14");
}

</style>
