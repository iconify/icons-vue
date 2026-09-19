<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ll0g54h-q"/><path class="tt6myf3rc"/><path class="hv-qkvb8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:maya" /></template>
<style>
.hv-qkvb8k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.722 21.581v3.646c0 1.22-.989 2.209-2.209 2.209h0a2.21 2.21 0 0 1-2.21-2.21v-3.645M9.5 23.79c0-1.22.99-2.209 2.21-2.209h0c1.22 0 2.209.99 2.209 2.21v3.645M9.5 21.581v5.855m4.419-3.646c0-1.22.989-2.209 2.209-2.209h0c1.22 0 2.21.99 2.21 2.21v3.645m6.695-2.209a2.21 2.21 0 0 1-2.21 2.209h0a2.21 2.21 0 0 1-2.209-2.21v-1.435c0-1.22.99-2.21 2.21-2.21h0c1.22 0 2.209.99 2.209 2.21m0 3.645v-5.855M38.5 25.227a2.21 2.21 0 0 1-2.21 2.209h0a2.21 2.21 0 0 1-2.209-2.21v-1.435c0-1.22.99-2.21 2.21-2.21h0c1.22 0 2.209.99 2.209 2.21m0 3.645v-5.855");
}

.ll0g54h-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

.tt6myf3rc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.722 25.227v2.982a2.21 2.21 0 0 1-2.209 2.21h0c-.61 0-1.162-.248-1.562-.647");
}

</style>
