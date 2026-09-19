<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vtmgmu2dh"/><path class="wt6v-7blf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ruffle" /></template>
<style>
.vtmgmu2dh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.473 20.436L7.294 42.5h8.916l3.678-25.523h-5.422a4.034 4.034 0 0 0-3.993 3.459");
}

.wt6v-7blf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.835 9.65l-.945 6.55l3.997.778l-.893 6.208h1.313a4.034 4.034 0 0 0 3.992-3.459l.862-5.984h5.998l-1.12 7.783h8.917L40.668 9.65a3.632 3.632 0 0 0-3.595-4.15H21.627a4.84 4.84 0 0 0-4.792 4.15");
}

</style>
