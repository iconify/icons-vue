<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9rmzobav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:siren-sharp" /></template>
<style>
.k9rmzobav {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 17v-4a4 4 0 1 1 8 0v4M5 17h14v4H5Zm7-4v4m0-14v2M4 5l2 2m14-2l-2 2");
}

</style>
