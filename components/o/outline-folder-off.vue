<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1t_3msip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-folder-off" /></template>
<style>
.r1t_3msip {
  fill: currentColor;
  d: path("M20 6h-8l-2-2H7.17l4 4H20v9.17l1.76 1.76c.15-.28.24-.59.24-.93V8c0-1.1-.9-2-2-2M2.1 2.1L.69 3.51l1.56 1.56c-.15.28-.24.59-.24.93L2 18c0 1.1.9 2 2 2h13.17l3.31 3.31l1.41-1.41zM4 18V6.83L15.17 18z");
}

</style>
