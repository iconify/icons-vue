<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ffx0q340q"/><path class="ds64m8b6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:netgear-nighthawk" /></template>
<style>
.ds64m8b6c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.906 24.396c8.742-7.525 19.991-5.824 26.513.94m-19.423 6.192c4.482-4.02 9.279-2.995 12.93.491");
}

.ffx0q340q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 17.307c8.836-8.026 26.72-11.58 39 1.091L24.177 37.936");
}

</style>
