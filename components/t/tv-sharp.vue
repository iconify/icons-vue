<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6-znbc-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tv-sharp" /></template>
<style>
.l6-znbc-o {
  fill: currentColor;
  d: path("M9 20v-2H3V4h18v14h-6v2z");
}

</style>
