<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o44zqbc7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:rate-review-outline-sharp" /></template>
<style>
.o44zqbc7e {
  fill: currentColor;
  d: path("M6 14h3.05l6.025-6.025L12.1 4.85L6 10.95zm7-6.075L12.075 7zM7.5 12.5v-.95l2.525-2.525l.5.45l.45.5L8.45 12.5zm3.025-3.025l.45.5l-.95-.95zm.65 4.525H18v-2h-4.825zM2 22V2h20v16H6zm3.15-6H20V4H4v13.125zM4 16V4z");
}

</style>
