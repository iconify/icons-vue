<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ndnyck2mv"/><path class="uhhi_-rna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:play-together" /></template>
<style>
.ndnyck2mv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.037 20.943l19.417-6.479a4.688 4.688 0 0 1 6.11 3.777c1.003 6.58.71 17.406-10.455 22.081a24.26 24.26 0 0 1-14.582 1.722");
}

.uhhi_-rna {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.963 27.057l-19.417 6.479a4.688 4.688 0 0 1-6.11-3.777c-1.003-6.58-.71-17.406 10.455-22.081a24.26 24.26 0 0 1 14.582-1.722");
}

</style>
