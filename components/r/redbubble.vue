<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x1fcr1bve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:redbubble" /></template>
<style>
.x1fcr1bve {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 13.259V34.74a1 1 0 0 0 1 1h17.748a1 1 0 0 0 .787-1.616l-6.054-7.733l.097-.057c4.492-2.597 5.083-8.847 1.158-12.24a7.55 7.55 0 0 0-4.934-1.836H5.5a1 1 0 0 0-1 1m21.997.001V34.74a1 1 0 0 0 1 1h8.36a7.45 7.45 0 0 0 5.643-2.584l.19-.22a7.45 7.45 0 0 0-.517-10.278s.298-.724.298-.724a7.007 7.007 0 0 0-6.478-9.676h-7.496a1 1 0 0 0-1 1");
}

</style>
