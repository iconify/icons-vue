<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnbc2pbdq"/><path class="xndakwhbn"/><path class="b0j4q4x6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-house" /></template>
<style>
.b0j4q4x6s {
  fill: currentColor;
  d: path("M10 10h4c0-1.1-.9-2-2-2s-2 .9-2 2");
}

.vnbc2pbdq {
  fill: currentColor;
  d: path("M7 10.19V18h2v-6h6v6h2v-7.81l-5-4.5zm7-.19h-4c0-1.1.9-2 2-2s2 .9 2 2");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.xndakwhbn {
  fill: currentColor;
  d: path("M19 9.3V4h-3v2.6L12 3L2 12h3v8h6v-6h2v6h6v-8h3zM17 18h-2v-6H9v6H7v-7.81l5-4.5l5 4.5z");
}

</style>
