<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzntyv2qb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:move-item-sharp" /></template>
<style>
.fzntyv2qb {
  fill: currentColor;
  d: path("M20.592 12.5H9.154v-1h11.438l-2.088-2.089l.707-.719L22.52 12l-3.307 3.308l-.708-.72zm-5.188-3.77V5H5v14h10.404v-3.73h1V20H4V4h12.404v4.73z");
}

</style>
