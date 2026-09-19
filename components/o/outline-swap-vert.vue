<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eutw0uboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-swap-vert" /></template>
<style>
.eutw0uboi {
  fill: currentColor;
  d: path("M16 17.01V10h-2v7.01h-3L15 21l4-3.99zM9 3L5 6.99h3V14h2V6.99h3zm7 14.01V10h-2v7.01h-3L15 21l4-3.99zM9 3L5 6.99h3V14h2V6.99h3z");
}

</style>
