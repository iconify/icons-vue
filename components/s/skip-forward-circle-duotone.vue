<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="wjr7gabtz"/><path class="wx4dtgx9p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:skip-forward-circle-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.wjr7gabtz {
  d: path("M128 32a96 96 0 1 0 96 96a96 96 0 0 0-96-96M96 168V88l64 40Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wx4dtgx9p {
  d: path("M160 80a8 8 0 0 0-8 8v25.57l-51.76-32.35A8 8 0 0 0 88 88v80a8 8 0 0 0 12.24 6.78L152 142.43V168a8 8 0 0 0 16 0V88a8 8 0 0 0-8-8m-56 73.57v-51.14L144.91 128ZM128 24a104 104 0 1 0 104 104A104.11 104.11 0 0 0 128 24m0 192a88 88 0 1 1 88-88a88.1 88.1 0 0 1-88 88");
}

</style>
