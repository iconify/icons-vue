<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a29uejbfv"/><path class="kty__eb4m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:toggle-left-bulk-sharp" /></template>
<style>
.a29uejbfv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 5h6a7 7 0 1 1 0 14H9A7 7 0 1 1 9 5");
}

.cuyn6tgcc {
  fill: currentColor;
}

.kty__eb4m {
  d: path("M5.315 10.443a4.001 4.001 0 0 1 7.37 3.114a4.001 4.001 0 0 1-7.37-3.114m1.842 2.335a2 2 0 1 0 3.686-1.556a2 2 0 0 0-3.686 1.556");
}

</style>
