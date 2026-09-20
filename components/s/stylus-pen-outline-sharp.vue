<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm9wejm6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stylus-pen-outline-sharp" /></template>
<style>
.wm9wejm6v {
  fill: currentColor;
  d: path("m6 16l2.5-9H10V5.5L11.5 2h1L14 5.5V7h1.5l2.5 9zm2.625-2h6.75l-1.4-5h-3.95zM4 21l1-3h14l1 3zm4.625-7h6.75z");
}

</style>
