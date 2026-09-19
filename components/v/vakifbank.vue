<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q3td0q3_r"/><path class="chmrgpbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vakifbank" /></template>
<style>
.chmrgpbjf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.988 13.468q-6.024.14-7.483 8.236L7.559 34.536h4.213c1.242.015 2.652-.544 3.588-1.495l7.61-8.753c2.6-3.029 4.858-5.345 7.061-7.28a50 50 0 0 1 4.335-3.409c-3.276-.604-7.22 1.323-10.741 4.998L13.083 29.46l2.186-10.15q1.104-4.224 4.533-5.72a10.6 10.6 0 0 0-1.814-.122");
}

.q3td0q3_r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.668 11.428c-9.666.022-11.772 3.417-13.406 12.555L4.5 36.573l28.103-.046c9.517.31 13.983-8.895 5.72-13.188c7.584-2.14 7.41-11.278-4.374-11.854l-13.28-.059z");
}

</style>
