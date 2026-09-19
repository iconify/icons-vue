<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="vbxvh4bkw"/><path class="vjn6upboo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:skylight" /></template>
<style>
.vbxvh4bkw {
  d: path("M11.618 38.208L7.748 16.38L26.574 4.5L30.6 26.226z");
}

.vjn6upboo {
  d: path("m28.572 14.622l7.652-4.83L40.25 31.52L21.269 43.5l-1.811-10.217");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
