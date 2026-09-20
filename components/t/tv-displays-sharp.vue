<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x071_zhcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tv-displays-sharp" /></template>
<style>
.x071_zhcd {
  fill: currentColor;
  d: path("M2 16V2h16v2H4v12zm9 6v-2H6V6h17v14h-5v2z");
}

</style>
