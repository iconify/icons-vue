<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vg8rk-xtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-share-outline-sharp" /></template>
<style>
.vg8rk-xtg {
  fill: currentColor;
  d: path("M8 16h2v-3h2.15l-1.05 1.1l1.4 1.4L16 12l-3.5-3.5l-1.4 1.4l1.05 1.1H8zm-3 7V1h14v5.1h1v4.8h-1V23zm2-2h10V3H7zm0 0V3z");
}

</style>
