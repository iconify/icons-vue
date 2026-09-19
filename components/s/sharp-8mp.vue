<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rsooluzsk"/><path class="h82e_gzkk"/><path class="ece932bmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-8mp" /></template>
<style>
.ece932bmi {
  fill: currentColor;
  d: path("M11.5 9H13v1.5h-1.5z");
}

.h82e_gzkk {
  fill: currentColor;
  d: path("M3 3v18h18V3zm7 2.5h4.5v6H10zm2.5 13H11V14h-1v3H8.5v-3h-1v4.5H6v-6h6.5zM18 17h-3v1.5h-1.5v-6H18z");
}

.rsooluzsk {
  fill: currentColor;
  d: path("M15 14h1.5v1.5H15zm-3.5-7.5H13V8h-1.5z");
}

</style>
