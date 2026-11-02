<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpzmsjlui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:traffic-cone-fill-sharp" /></template>
<style>
.lpzmsjlui {
  fill: currentColor;
  d: path("M15.677 9H8.323l1.749-4.371A1 1 0 0 1 11 4h2c.409 0 .777.249.928.629Zm2 5H6.323l1.2-3h8.954ZM3 21a1 1 0 0 1 0-2h1.323l1.2-3h12.954l1.2 3H21a1 1 0 0 1 0 2Z");
}

</style>
