<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ymn5cnysj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:vehicle-trailer-20-regular" /></template>
<style>
.ymn5cnysj {
  fill: currentColor;
  d: path("M13.154 3.004A3 3 0 0 1 16 6v8h2v-1.5a.5.5 0 0 1 1 0v4a.5.5 0 0 1-1 0V15H8.95a2.501 2.501 0 0 1-4.9 0H4a3 3 0 0 1-3-3a9 9 0 0 1 9-9h3zM6.5 13a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3M10 4a8 8 0 0 0-8 8a2 2 0 0 0 2 2h.05a2.501 2.501 0 0 1 4.9 0H15V6a2 2 0 0 0-1.796-1.99L13 4zm2 2a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1zm-3 4h3V7H9z");
}

</style>
