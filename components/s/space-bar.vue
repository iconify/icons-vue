<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klvgiqbuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:space-bar" /></template>
<style>
.klvgiqbuv {
  fill: currentColor;
  d: path("M18 9v4H6V9H4v6h16V9z");
}

</style>
