<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tnup15m0x"/><path class="tumqbkb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nest" /></template>
<style>
.tnup15m0x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 7.15L4.5 22.4l2.588 3.31l2.997-2.345v17.486h27.83V23.365l2.997 2.344L43.5 22.4l-5.585-4.367v-6.145h-3.103v3.652z");
}

.tumqbkb3h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.009 40.85V29.064a5.009 5.009 0 0 0-10.017 0v11.788");
}

</style>
