<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ll0g54h-q"/><path class="orney0b1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ssi-iboard" /></template>
<style>
.ll0g54h-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

.orney0b1m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.812 30.247c.98 1.277 2.211 1.753 3.923 1.753h2.369a3.99 3.99 0 0 0 3.991-3.991v-.017A3.99 3.99 0 0 0 17.104 24H14.49a3.996 3.996 0 0 1-3.996-3.996h0A4.004 4.004 0 0 1 14.499 16h2.356c1.712 0 2.942.476 3.923 1.753m3.434 12.494c.98 1.277 2.211 1.753 3.923 1.753h2.369a3.99 3.99 0 0 0 3.991-3.991v-.017A3.99 3.99 0 0 0 30.504 24H27.89a3.996 3.996 0 0 1-3.996-3.996h0A4.004 4.004 0 0 1 27.899 16h2.356c1.712 0 2.942.476 3.923 1.753M37.505 32V16");
}

</style>
