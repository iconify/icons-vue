<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9wf6kb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:redo-fill" /></template>
<style>
.s9wf6kb_f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 18C2 11.6487 7.1487 6.5 13.5 6.5C16.55 6.5 19.4751 7.7116 21.6317 9.8683M22 6L22 9.7365C22 10.0127 21.7761 10.2365 21.5 10.2365L17.7635 10.2365");
}

</style>
