<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c01iphben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stylus-pen" /></template>
<style>
.c01iphben {
  fill: currentColor;
  d: path("m6 16l2.5-9H10V5.5L11.5 2h1L14 5.5V7h1.5l2.5 9zm-2 5l.55-1.625q.2-.625.725-1T6.45 18h11.1q.65 0 1.175.375t.725 1L20 21z");
}

</style>
