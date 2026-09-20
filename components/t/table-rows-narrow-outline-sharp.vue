<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l0uo3iprf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:table-rows-narrow-outline-sharp" /></template>
<style>
.l0uo3iprf {
  fill: currentColor;
  d: path("M5 15h14v-2H5zm0-4h14V9H5zm0-4h14V5H5zM3 21V3h18v18zm2-2h14v-2H5z");
}

</style>
