<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5l6khpjk"/><circle class="p4d382b4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-screen-search-desktop" /></template>
<style>
.p4d382b4m {
  cx: 11.5px;
  cy: 10px;
  r: 2px;
  fill: currentColor;
}

.q5l6khpjk {
  fill: currentColor;
  d: path("M1 19h22v2H1zM22 3H2v15h19.99zm-6.53 12.03l-2.09-2.09c-1.35.87-3.17.71-4.36-.47c-1.37-1.37-1.37-3.58 0-4.95s3.58-1.37 4.95 0c1.18 1.18 1.34 3 .47 4.36l2.09 2.09z");
}

</style>
