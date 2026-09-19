<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f15mgiznz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-escalator" /></template>
<style>
.f15mgiznz {
  fill: currentColor;
  d: path("M21 3H3v18h18zm-2.5 6h-3.2l-5 9H5.5v-3h3.2l5-9h4.8z");
}

</style>
