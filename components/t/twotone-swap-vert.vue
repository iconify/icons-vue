<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-x5mhb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-swap-vert" /></template>
<style>
.s-x5mhb3w {
  fill: currentColor;
  d: path("M16 17.01V10h-2v7.01h-3L15 21l4-3.99zM9 3L5 6.99h3V14h2V6.99h3z");
}

</style>
