<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ty2ricpyy"/><path class="d8zng-brd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:subway" /></template>
<style>
.d8zng-brd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.1 43.5l-8.3-6.6l8.3-6.6v3.3h7.2c6.7.1 9.1-7.5 2.1-10.6l-3.6-1.7c-.6-.2-.9-.9.2-.8h11.1c8.5 4.8 6.3 19.4-8.5 19.6H17Z");
}

.ty2ricpyy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.9 4.5l8.3 6.6l-8.3 6.6v-3.3h-7.2c-6.7-.1-9.1 7.5-2.1 10.6l3.6 1.7c.6.2.9.9-.2.8H13.8C5.3 22.6 7.5 7.9 22.3 7.8h8.6Z");
}

</style>
