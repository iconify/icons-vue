<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ci2i2lbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:thumbs-down-sharp" /></template>
<style>
.ci2i2lbco {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 14a4 4 0 0 1 4 4v1a2 2 0 1 0 4 0v-5h6v-4l-2-7H7m0 11H3V3h4z");
}

</style>
