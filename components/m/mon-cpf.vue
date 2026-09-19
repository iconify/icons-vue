<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i2-zaubeg"/><path class="g2wj9jbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mon-cpf" /></template>
<style>
.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.i2-zaubeg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.914 28.388V19.5l4.5 9l4.5-9v9m9.472-3.091a3.026 3.026 0 0 1-3.038 3.037h0c-1.687 0-3.037-1.35-3.037-2.925v-3.037c0-1.687 1.35-3.036 3.037-2.923h0c1.687 0 2.923 1.348 2.923 2.923h0M32.587 24h2.924m-2.924 4.5v-9h4.499");
}

</style>
