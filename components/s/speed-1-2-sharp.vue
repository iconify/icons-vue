<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nd_hy_bmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:speed-1-2-sharp" /></template>
<style>
.nd_hy_bmb {
  fill: currentColor;
  d: path("M7 17V9H5V7h4v10zm3 0v-2h2v2zm3 0v-6h4V9h-4V7h6v6h-4v2h4v2z");
}

</style>
