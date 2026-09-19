<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ydqthzbbt"/><path class="dnr742c-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tldr" /></template>
<style>
.dnr742c-i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.204 30.247c.98 1.277 2.211 1.753 3.923 1.753h2.369a3.996 3.996 0 0 0 3.991-4h0c0-2.21-1.787-4-3.991-4h-2.618a3.996 3.996 0 0 1-3.991-4h0c0-2.21 1.787-4 3.991-4h2.37c1.71 0 2.941.476 3.922 1.753M17.187 34V14m8.326 20h10.6");
}

.ydqthzbbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 42.5h-29c-2.2 0-4-1.8-4-4v-29c0-2.2 1.8-4 4-4h29c2.2 0 4 1.8 4 4v29c0 2.2-1.8 4-4 4");
}

</style>
