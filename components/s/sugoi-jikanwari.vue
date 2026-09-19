<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ll0g54h-q"/><path class="tjiv38b8a"/><path class="axqm8-b9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sugoi-jikanwari" /></template>
<style>
.axqm8-b9x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.031 17.5v8.031a4.969 4.969 0 1 0 9.938 0V17.5m-11.813 0h3.75m6.188 0h3.75");
}

.ll0g54h-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

.tjiv38b8a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.3 37.5H14.7c-2.3 0-4.1-1.9-4.1-4.1V14.7c0-2.3 1.9-4.1 4.1-4.1h18.7c2.3 0 4.1 1.9 4.1 4.1v18.7c0 2.2-1.9 4.1-4.2 4.1M5.5 14.8h5m-5 9.2h5m-5 9.2h5M33.2 5.5v5m-9.2-5v5m-9.2-5v5m18.4 27v5m-9.2-5v5m-9.2-5v5m22.7-27.7h5m-5 9.2h5m-5 9.2h5");
}

</style>
