<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rec5gmbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:post" /></template>
<style>
.rec5gmbbj {
  fill: currentColor;
  d: path("M3 21V3h18v18zm3-7h12v-2H6zm0 3h12v-1.5H6z");
}

</style>
