<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="c5vr70bhb"/><path class="pi1wcd4wl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:stack-simple-fill" /></template>
<style>
.c5vr70bhb {
  d: path("m12 111l112 64a8 8 0 0 0 7.94 0l112-64a8 8 0 0 0 0-13.9l-112-64a8 8 0 0 0-7.94 0l-112 64a8 8 0 0 0 0 13.9");
}

.cuyn6tgcc {
  fill: currentColor;
}

.pi1wcd4wl {
  d: path("m236 137.05l-108 61.74l-108-61.74A8 8 0 1 0 12 151l112 64a8 8 0 0 0 7.94 0l112-64a8 8 0 1 0-7.94-13.9Z");
}

</style>
