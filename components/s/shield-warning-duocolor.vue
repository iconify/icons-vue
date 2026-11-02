<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n7g8cbgkv"/><path class="efwzxob8a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-warning-duocolor" /></template>
<style>
.efwzxob8a {
  d: path("M12 3h6a2 2 0 0 1 2 2v5c0 5.5-3.5 9-8 11c-4.5-2-8-5.5-8-11V5a2 2 0 0 1 2-2z");
}

.n7g8cbgkv {
  stroke-opacity: 0.4;
  d: path("M12 8v4m0 3h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
