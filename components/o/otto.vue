<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s53wggb1x"/><path class="v7mqrbb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:otto" /></template>
<style>
.s53wggb1x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4M18.651 20h5.3m-4.061 8l1.411-8m4.331 0h5.3m-4.06 8l1.41-8");
}

.v7mqrbb0c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.316 28zc-1.464 0-2.441-1.186-2.183-2.65l.476-2.7c.258-1.464 1.654-2.65 3.117-2.65s2.441 1.186 2.183 2.65l-.476 2.7c-.258 1.464-1.654 2.65-3.117 2.65m19.958 0zc-1.464 0-2.441-1.186-2.183-2.65l.476-2.7c.258-1.464 1.654-2.65 3.117-2.65s2.441 1.186 2.183 2.65l-.476 2.7c-.258 1.464-1.654 2.65-3.117 2.65");
}

</style>
