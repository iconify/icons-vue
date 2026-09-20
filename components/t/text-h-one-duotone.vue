<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="m4vl1h_ly"/><path class="skxtiu_0m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:text-h-one-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.m4vl1h_ly {
  d: path("M224 72v136H56a16 16 0 0 1-16-16V56h168a16 16 0 0 1 16 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.skxtiu_0m {
  d: path("M152 56v120a8 8 0 0 1-16 0v-52H48v52a8 8 0 0 1-16 0V56a8 8 0 0 1 16 0v52h88V56a8 8 0 0 1 16 0m75.77 49a8 8 0 0 0-8.21.39l-24 16a8 8 0 1 0 8.88 13.32L216 127v81a8 8 0 0 0 16 0v-96a8 8 0 0 0-4.23-7");
}

</style>
