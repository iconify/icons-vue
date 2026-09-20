<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zg2v8ab0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:trackpad-input-sharp" /></template>
<style>
.zg2v8ab0v {
  fill: currentColor;
  d: path("M2 19V3h19v6h-2V5H4v12h1.8l1.975 2zm17 3h-4.175q-.6 0-1.15-.225t-.975-.65L7.6 16l1.6-1.65l2.8.825V7h2v7h1v-4h2v4h1v-3h2v3h1v-1h2v5q0 1.65-1.175 2.825T19 22");
}

</style>
