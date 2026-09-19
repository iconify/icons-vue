<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lww3kobke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-bookmark-added" /></template>
<style>
.lww3kobke {
  fill: currentColor;
  d: path("m19 21l-7-3l-7 3V3h9a5.002 5.002 0 0 0 5 7.9zM17.83 9L15 6.17l1.41-1.41l1.41 1.41l3.54-3.54l1.41 1.41z");
}

</style>
