<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ita66hn8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:star-of-david" /></template>
<style>
.ita66hn8w {
  fill: var(--svg-color--c28fef, #c28fef);
  d: path("M58 17.4H41L32 2l-9 15.4H6L14.5 32L6 46.6h17L32 62l9-15.4h17L49.5 32zM51.9 21l-4.4 7.5l-4.4-7.5zM32 9l4.9 8.4H27zM12.1 21h8.8l-4.4 7.5zm0 22l4.4-7.5l4.4 7.5zM32 55l-4.9-8.4H37zm7-12H25l-6.4-11L25 21h14l6.4 11zm12.9 0h-8.8l4.4-7.5z");
}

</style>
