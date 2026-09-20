<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yhge5hb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:usb-off-20-filled" /></template>
<style>
.yhge5hb_k {
  fill: currentColor;
  d: path("M2.146 2.146a.5.5 0 0 1 .707 0l15 15a.5.5 0 0 1-.707.707l-5.405-5.405l-.574.515a1.25 1.25 0 0 0-.417.932v1.252a2 2 0 1 1-1.691.087a1.3 1.3 0 0 0-.226-.271l-3.417-3.058a2.75 2.75 0 0 1-.916-2.05V9.33A1.748 1.748 0 0 1 5.25 6l.045.002l-3.149-3.148a.5.5 0 0 1 0-.708M7 7.75c0 .698-.41 1.298-1 1.58v.525c0 .356.152.695.417.932l2.833 2.534V9.957L6.997 7.704zM15.75 4a.75.75 0 0 1 .75.75v2a.75.75 0 0 1-.75.75h-.25v.355a2.75 2.75 0 0 1-.916 2.05l-1.35 1.207l-1.063-1.062l1.412-1.263A1.25 1.25 0 0 0 14 7.855V7.5h-.25a.75.75 0 0 1-.75-.75v-2a.75.75 0 0 1 .75-.75zM9.368.852a.75.75 0 0 1 1.272 0l1.249 1.995a.75.75 0 0 1-.636 1.147h-.503V8.63l-1.5-1.5V3.994h-.495a.75.75 0 0 1-.636-1.147z");
}

</style>
