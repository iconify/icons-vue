<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="clp2a2b3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:smugmug" /></template>
<style>
.clp2a2b3y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.72 22.643c1.038-1.687 7.667-.391 14.774-.714c6.968-.317 13.52-1.947 14.817-.26c1.626 2.115-6.62 20.831-19.857 20.831S7.885 25.622 9.72 22.643m6.813-16.705c-1.817 0-4.023 1.428-4.023 3.05s.973 2.726 3.115 2.726s4.607-.844 4.607-2.888s-1.622-2.888-3.699-2.888M35.086 5.5c-1.817 0-4.023 1.428-4.023 3.05s.973 2.726 3.115 2.726s4.607-.844 4.607-2.888S37.163 5.5 35.086 5.5");
}

</style>
