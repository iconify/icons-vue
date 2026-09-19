<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iddbs3bxt"/><path class="nw9bnfbfi"/><path class="ibzyhx7cz"/><path class="dxktfcc8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:qwen" /></template>
<style>
.dxktfcc8j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.375 44.86l5.884-.618l4.995-8.652l5.925-.687l3.176-5.501");
}

.ibzyhx7cz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.762 12.979l-2.407 5.404l4.995 8.652l-2.367 5.475l3.176 5.501m25.904-13.396l2.367 5.474l5.925-.687l-4.734-10.949h-5.528L21.008 39.386l2.367 5.474z");
}

.iddbs3bxt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.802 13.666l3.557-4.787l-3.557-4.787l-7.116 9.574l2.764 4.787h24.171l3.557-4.787z");
}

.nw9bnfbfi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.178 13.666l-3.477-4.787h-9.99l-3.557-4.787h-6.352M17.45 33.224l-5.924-.688l-2.367 5.475l11.849 1.375l2.764-4.788l-12.086-20.932l-5.924-.687z");
}

</style>
