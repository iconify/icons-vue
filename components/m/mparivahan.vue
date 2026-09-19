<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m4bohibjn"/><path class="wuzsvvb9v"/><circle class="j355e4lau"/><circle class="phnnl9obg"/><path class="lqjl04b8t"/><path class="tazbezbaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mparivahan" /></template>
<style>
.j355e4lau {
  cx: 36.935px;
  cy: 26.811px;
  r: 1.366px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.lqjl04b8t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.719 34.026h10.657a1.62 1.62 0 0 0 1.622-1.622h0a1.62 1.62 0 0 0-1.621-1.621H18.06a1.62 1.62 0 0 0-1.622 1.621h0a1.62 1.62 0 0 0 1.622 1.622Zm6.021-10.64c0-1.148-.956-2.059-2.906-2.059s-2.332 1.039-2.332 2.06");
}

.m4bohibjn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.166 26.811h7.105m-7.105 1.84h7.105m-8.957 5.375v1.124a1.366 1.366 0 1 1-2.733 0v-1.124m16.275 0v1.124a1.366 1.366 0 1 1-2.733 0v-1.124m-11.426-10.64c0-1.148.957-2.059 2.906-2.059s2.332 1.039 2.332 2.06");
}

.phnnl9obg {
  cx: 20.502px;
  cy: 26.811px;
  r: 1.366px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tazbezbaj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.719 16.682V7.099a2.6 2.6 0 0 0-2.6-2.599H9.601a2.6 2.6 0 0 0-2.599 2.6v33.8a2.6 2.6 0 0 0 2.6 2.6h16.517a2.6 2.6 0 0 0 2.6-2.6v-6.874");
}

.wuzsvvb9v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.761 31.202v-3.826c0-1.366-.305-2.522-1.275-3.06a3.18 3.18 0 0 1-1.421-1.859a169 169 0 0 0-1.603-3.753a3.76 3.76 0 0 0-2.715-1.877c-.729-.073-2.077-.145-5.028-.145s-4.3.073-5.029.145a3.76 3.76 0 0 0-2.714 1.877a166 166 0 0 0-1.603 3.753a3.18 3.18 0 0 1-1.422 1.858c-.97.54-1.275 1.695-1.275 3.061v3.826M38.5 23.386H18.937");
}

</style>
