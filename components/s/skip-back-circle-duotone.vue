<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="e0godxbzl"/><path class="nl0n8abhk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:skip-back-circle-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.e0godxbzl {
  d: path("M128 32a96 96 0 1 0 96 96a96 96 0 0 0-96-96m32 136l-64-40l64-40Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nl0n8abhk {
  d: path("M128 24a104 104 0 1 0 104 104A104.11 104.11 0 0 0 128 24m0 192a88 88 0 1 1 88-88a88.1 88.1 0 0 1-88 88m35.88-135a8 8 0 0 0-8.12.22L104 113.57V88a8 8 0 0 0-16 0v80a8 8 0 0 0 16 0v-25.57l51.76 32.35A8 8 0 0 0 168 168V88a8 8 0 0 0-4.12-7M152 153.57L111.09 128L152 102.43Z");
}

</style>
