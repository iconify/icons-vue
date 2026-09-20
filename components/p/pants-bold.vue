<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="v84hrnbzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:pants-bold" /></template>
<style>
.v84hrnbzv {
  fill: currentColor;
  d: path("m227.85 213.52l-22-176A20 20 0 0 0 186 20H70a20 20 0 0 0-19.85 17.52l-22 176A20 20 0 0 0 48 236h40.69a19.94 19.94 0 0 0 19.38-15L128 144l19.91 76.94a20 20 0 0 0 19.4 15.06H208a20 20 0 0 0 19.85-22.48M182.47 44l2 16H71.53l2-16ZM85.6 212H52.53l11.2-89.6A44.11 44.11 0 0 0 95.81 84H116v10.47Zm84.81 0L140 94.47V84h20.19a44.09 44.09 0 0 0 32.08 38.39l11.2 89.61Z");
}

</style>
