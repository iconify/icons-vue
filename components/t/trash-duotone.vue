<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="n3eg_ob3b"/><path class="uz12vzfhs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:trash-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.n3eg_ob3b {
  d: path("M200 56v152a8 8 0 0 1-8 8H64a8 8 0 0 1-8-8V56Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uz12vzfhs {
  d: path("M216 48h-40v-8a24 24 0 0 0-24-24h-48a24 24 0 0 0-24 24v8H40a8 8 0 0 0 0 16h8v144a16 16 0 0 0 16 16h128a16 16 0 0 0 16-16V64h8a8 8 0 0 0 0-16M96 40a8 8 0 0 1 8-8h48a8 8 0 0 1 8 8v8H96Zm96 168H64V64h128Zm-80-104v64a8 8 0 0 1-16 0v-64a8 8 0 0 1 16 0m48 0v64a8 8 0 0 1-16 0v-64a8 8 0 0 1 16 0");
}

</style>
