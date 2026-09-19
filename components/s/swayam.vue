<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="akgtkvahg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:swayam" /></template>
<style>
.akgtkvahg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.97 36.47C10.083 36.47 4.5 30.887 4.5 24s5.583-12.47 12.47-12.47h14.06c6.887 0 12.47 5.583 12.47 12.47s-5.583 12.47-12.47 12.47zm2.701-24.94v24.94m0-12.47H4.5");
}

</style>
