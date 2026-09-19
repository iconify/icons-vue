<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mb_bxsbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-space-bar" /></template>
<style>
.mb_bxsbbi {
  fill: currentColor;
  d: path("M18 13H6V9H4v6h16V9h-2z");
}

</style>
