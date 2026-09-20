<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qd077oh-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:trending-up" /></template>
<style>
.qd077oh-y {
  fill: currentColor;
  d: path("M3.4 18L2 16.6l7.4-7.45l4 4L18.6 8H16V6h6v6h-2V9.4L13.4 16l-4-4z");
}

</style>
