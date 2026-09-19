<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srjn1b4iv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-airline-seat-legroom-normal" /></template>
<style>
.srjn1b4iv {
  fill: currentColor;
  d: path("M5 15V3H3v14h11v-2zm17 3h-3v-7c0-1.1-.9-2-2-2h-5V3H6v11h10v7h6z");
}

</style>
