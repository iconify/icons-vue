<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zi5gct-lp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-difference" /></template>
<style>
.zi5gct-lp {
  fill: currentColor;
  d: path("M18 23H2V7h2v14h14zM15 1H6.01L6 19h15V7zm1.5 14h-6v-2h6zm0-6h-2v2h-2V9h-2V7h2V5h2v2h2z");
}

</style>
