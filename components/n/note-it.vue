<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k9lh7wb3k"/><path class="nab3jqbkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:note-it" /></template>
<style>
.k9lh7wb3k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.038 12.488a1.84 1.84 0 0 0-1.842-1.842H8.804a1.84 1.84 0 0 0-1.842 1.842v23.024a1.84 1.84 0 0 0 1.842 1.842h30.392a1.84 1.84 0 0 0 1.842-1.842Z");
}

.nab3jqbkc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38.06 10.646l-.582-2.176a1.84 1.84 0 0 0-2.256-1.302l-12.98 3.478M41.038 33.26l1.096-.294a1.84 1.84 0 0 0 1.303-2.256l-2.4-8.953M9.94 37.354l.582 2.176a1.84 1.84 0 0 0 2.256 1.302l12.98-3.478M6.962 14.74l-1.096.294a1.84 1.84 0 0 0-1.303 2.256l2.414 9.008m5.971-10.126h22.103m-22.103 5.219h22.103m-22.103 5.218h22.103m-22.103 5.219H24");
}

</style>
