<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rqwimvb0p"/><path class="dmvlytb3y"/><path class="owuafibie"/><path class="czieoxuyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:qwen-alt-1" /></template>
<style>
.czieoxuyg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.375 44.86l5.884-.618l4.995-8.651l5.925-.688l3.176-5.501");
}

.dmvlytb3y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.178 13.666L38.701 8.88h-9.99l-3.557-4.787h-6.352M17.45 33.224l-5.924-.688l-2.367 5.475l11.849 1.374l2.764-4.787l-12.086-20.932l-5.924-.687z");
}

.owuafibie {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.762 12.979l-2.407 5.404l4.995 8.652l-2.367 5.475l3.176 5.5m25.904-13.395l2.367 5.474l5.925-.687l-4.734-10.949h-5.528L21.008 39.386l2.367 5.474z");
}

.rqwimvb0p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.802 13.666l3.557-4.787l-3.558-4.787l-7.115 9.574l2.764 4.787h24.17l3.558-4.787z");
}

</style>
