<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynmdx1bza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-emoji-food-beverage" /></template>
<style>
.ynmdx1bza {
  fill: currentColor;
  d: path("M2 19h18v2H2zM20 3H9v2.4L11 7v5H6V7l2-1.6V3H4v14h14v-7h2c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 5h-2V5h2z");
}

</style>
