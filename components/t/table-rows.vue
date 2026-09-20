<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkpuntb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:table-rows" /></template>
<style>
.lkpuntb9t {
  fill: currentColor;
  d: path("M20 20H4v-4.592h16zm0-5.592H4V9.587h16zm0-5.821H4V4h16z");
}

</style>
