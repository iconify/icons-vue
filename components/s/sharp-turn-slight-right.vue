<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3k5amnsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-turn-slight-right" /></template>
<style>
.v3k5amnsa {
  fill: currentColor;
  d: path("M12.34 6V4H18v5.66h-2V7.41l-5 5V20H9v-8.41L14.59 6z");
}

</style>
