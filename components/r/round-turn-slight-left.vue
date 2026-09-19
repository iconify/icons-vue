<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b04alpbef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-turn-slight-left" /></template>
<style>
.b04alpbef {
  fill: currentColor;
  d: path("M11.66 5c0-.55-.45-1-1-1H7c-.55 0-1 .45-1 1v3.66c0 .55.45 1 1 1s1-.45 1-1V7.41l5 5V19c0 .55.45 1 1 1s1-.45 1-1v-6.58c0-.53-.21-1.04-.59-1.41l-5-5h1.24A1.02 1.02 0 0 0 11.66 5");
}

</style>
