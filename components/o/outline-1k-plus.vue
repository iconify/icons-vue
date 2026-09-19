<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pljig0b1n"/><path class="zpsz44bsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-1k-plus" /></template>
<style>
.pljig0b1n {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 8.5h-1.5V10h-1v1.5H15v1h1.5V14h1v-1.5H19V19H5V5h14z");
}

.zpsz44bsp {
  fill: currentColor;
  d: path("M7.5 15H9V9H6v1.5h1.5zm4.5-2.25L13.75 15h1.75l-2.25-3l2.25-3h-1.75L12 11.25V9h-1.5v6H12z");
}

</style>
