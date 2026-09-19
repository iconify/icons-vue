<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fe9tcc1gq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-turn-sharp-left" /></template>
<style>
.fe9tcc1gq {
  fill: currentColor;
  d: path("M6 6.83L4.41 8.41L3 7l4-4l4 4l-1.41 1.41L8 6.83V13h8c1.1 0 2 .9 2 2v6h-2v-6H8c-1.1 0-2-.9-2-2z");
}

</style>
