<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zc9kiccea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tapnturn" /></template>
<style>
.zc9kiccea {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24A21.51 21.51 0 0 0 24 2.5l7.23 7.24l4.09-4M18.14 4.17a2.1 2.1 0 0 0-1.47.61L4.78 16.67a2.07 2.07 0 0 0 0 2.93L28.4 43.22a2.07 2.07 0 0 0 2.93 0l11.89-11.89a2.08 2.08 0 0 0 0-2.94L19.61 4.78a2.1 2.1 0 0 0-1.47-.61M2.5 24A21.51 21.51 0 0 0 24 45.5l-7.23-7.24l-4.09 4M6.91 21.73L21.73 6.91m4.54 34.18l14.82-14.83");
}

</style>
