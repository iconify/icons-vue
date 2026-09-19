<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q_5r2rsjw"/><path class="c2xrbabwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:naranja-x" /></template>
<style>
.c2xrbabwq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 19.6v18.9a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4z");
}

.q_5r2rsjw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.014 26.436l4.486 6.77M26.302 14.794L32.401 24m0 0l-6.099 9.206M38.5 14.794l-4.486 6.77M9.5 33.206V14.794l12.198 18.412V14.794");
}

</style>
