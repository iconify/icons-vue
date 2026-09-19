<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkb2-3cdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-10mp" /></template>
<style>
.kkb2-3cdp {
  fill: currentColor;
  d: path("M13.5 7H15v3h-1.5zM21 3H3v18h18zm-8.5 15.5H11V14h-1v3H8.5v-3h-1v4.5H6v-6h6.5zm2.5 0h-1.5v-6H18V17h-3zm-5-13v6H8.5V7H7V5.5zm6.5 0v6H12v-6zM15 14h1.5v1.5H15z");
}

</style>
