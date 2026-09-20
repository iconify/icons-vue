<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gujxuz3qc"/><path class="of2t7m18c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:swish-payments" /></template>
<style>
.gujxuz3qc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5c-11.874.003-21.497 9.632-21.494 21.506A21.5 21.5 0 0 0 8.8 39.2l6.91-6.9c-6.49-6.487-6.492-17.006-.005-23.495S32.711 2.313 39.2 8.8A21.43 21.43 0 0 0 24 2.5");
}

.of2t7m18c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 45.5c11.874-.003 21.498-9.631 21.494-21.506A21.5 21.5 0 0 0 39.2 8.8l-6.91 6.9c6.49 6.487 6.492 17.006.005 23.495S15.289 45.687 8.8 39.2A21.43 21.43 0 0 0 24 45.5");
}

</style>
