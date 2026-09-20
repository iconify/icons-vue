<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="w_ws4bb7i"/><path class="a5x7_vbns"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:wave-square-duotone" /></template>
<style>
.a5x7_vbns {
  d: path("M240 128v56a8 8 0 0 1-8 8H128a8 8 0 0 1-8-8V80H32v48a8 8 0 0 1-16 0V72a8 8 0 0 1 8-8h104a8 8 0 0 1 8 8v104h88v-48a8 8 0 0 1 16 0");
}

.cuyn6tgcc {
  fill: currentColor;
}

.w_ws4bb7i {
  d: path("M128 72v56H24V72Zm0 56v56h104v-56Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
