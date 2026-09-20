<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yyme27cps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:margin-outline-sharp" /></template>
<style>
.yyme27cps {
  fill: currentColor;
  d: path("M3 21V3h18v18zm2-2h14V5H5zm0 0V5zM7 9V7h2v2zm4 0V7h2v2zm4 0V7h2v2zm-8 4v-2h2v2zm4 0v-2h2v2zm4 0v-2h2v2z");
}

</style>
