<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="r4bt0cv2m"/><path clip-rule="evenodd" class="npbii8bhv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:toggles-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.npbii8bhv {
  fill-rule: evenodd;
  d: path("M4.5 1L19.5 1C20.3284 1 21 1.6716 21 2.5L21 9.5C21 10.3284 20.3284 11 19.5 11L4.5 11C3.6716 11 3 10.3284 3 9.5L3 2.5C3 1.6716 3.6716 1 4.5 1ZM4.5 13L19.5 13C20.3284 13 21 13.6716 21 14.5L21 21.5C21 22.3284 20.3284 23 19.5 23L4.5 23C3.6716 23 3 22.3284 3 21.5L3 14.5C3 13.6716 3.6716 13 4.5 13ZM5 3L5 9L11 9L11 3L5 3ZM13 15L13 21L19 21L19 15L13 15Z");
}

.r4bt0cv2m {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 3L11 3L11 9L5 9ZM13 15L19 15L19 21L13 21Z");
}

</style>
