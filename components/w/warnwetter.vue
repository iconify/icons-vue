<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aoq_xl6jh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:warnwetter" /></template>
<style>
.aoq_xl6jh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.93 43.5l16.87-14h-9.53l3.56-6.41h-7L15.56 33h7.79Zm-4.55-20.4h19.27c10.46 0 8.71-15.74-1.78-12.25c0-8.74-15.74-8.74-15.74 1.75c-8.75-1.75-8.75 10.5-1.75 10.5");
}

</style>
