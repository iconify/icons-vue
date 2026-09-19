<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e--7bvhup"/><path class="ydqthzbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:uuid0xfd6fscanner" /></template>
<style>
.e--7bvhup {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.68 21.092c.715 1.85.715 4.199 0 6.05m4.01 3.952c2.677-4.068 2.677-9.886 0-13.954M13.303 31.07l13.872-13.802l-6.779-6.768v27l6.779-6.768L13.303 16.93");
}

.ydqthzbbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 42.5h-29c-2.2 0-4-1.8-4-4v-29c0-2.2 1.8-4 4-4h29c2.2 0 4 1.8 4 4v29c0 2.2-1.8 4-4 4");
}

</style>
