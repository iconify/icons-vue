<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usza71brl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-stairs" /></template>
<style>
.usza71brl {
  fill: currentColor;
  d: path("M3 3v18h18V3zm15 5h-2.42v3.33H13v3.33h-2.58V18H6v-2h2.42v-3.33H11V9.33h2.58V6H18z");
}

</style>
