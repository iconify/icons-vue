<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnv018bot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-screensaver-outline-sharp" /></template>
<style>
.gnv018bot {
  fill: currentColor;
  d: path("M5 23V1h14v5.1h1v4.8h-1V23zm2-2h10V3H7zm1-6h8l-2.625-3.5L11.5 14l-1.375-1.825zm7.713-5.288Q16 9.425 16 9t-.288-.712T15 8t-.712.288T14 9t.288.713T15 10t.713-.288M7 21V3z");
}

</style>
