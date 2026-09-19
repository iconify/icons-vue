<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2yt9ebjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-lan" /></template>
<style>
.n2yt9ebjh {
  fill: currentColor;
  d: path("M13 22h8v-7h-3v-4h-5V9h3V2H8v7h3v2H6v4H3v7h8v-7H8v-2h8v2h-3zM10 7V4h4v3zM9 17v3H5v-3zm10 0v3h-4v-3z");
}

</style>
