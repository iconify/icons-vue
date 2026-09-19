<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x9t59pb0m"/><path class="msotdfb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:my-telstra" /></template>
<style>
.msotdfb8m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.42 21.495c7.415 6.633 10.596 15.143 7.124 19.056c-3.492 3.934-12.403 1.726-19.889-4.937C9.16 28.961 5.918 20.381 9.41 16.448c2.358-2.66 7.205-2.509 12.403-.07");
}

.x9t59pb0m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.796 32.481l3.764-20.078h-8.157c0-7.127 4.393-6.902 4.393-6.902l21.199.158c0 6.871-3.63 6.744-3.63 6.744h-5.647l-2.51 17.569s-.63 2.51-2.51 2.51z");
}

</style>
