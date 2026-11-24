<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k41deub1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-edit-corner-round" /></template>
<style>
.k41deub1a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 8v8a4 4 0 0 0 4 4M4 8l1-2c.613-1.226 1.774-2 3-2h8c1.226 0 2.387.774 3 2l1 2M4 8h16m-7 13v-3l5-5l3 3l-5 5Z");
}

</style>
