<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="mfyo8rb6u"/><path class="bvb8bcyns"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:text-h-six-duotone" /></template>
<style>
.bvb8bcyns {
  d: path("M152 56v120a8 8 0 0 1-16 0v-52H48v52a8 8 0 0 1-16 0V56a8 8 0 0 1 16 0v52h88V56a8 8 0 0 1 16 0m96 124a36 36 0 1 1-67.34-17.68c.07-.14.14-.28.22-.42l32.25-54a8 8 0 0 1 13.74 8.2l-16.69 28c.6 0 1.21-.05 1.82-.05A36 36 0 0 1 248 180m-16 0a20 20 0 1 0-20 20a20 20 0 0 0 20-20");
}

.cuyn6tgcc {
  fill: currentColor;
}

.mfyo8rb6u {
  d: path("M240 72v120a16 16 0 0 1-16 16H56a16 16 0 0 1-16-16V56h184a16 16 0 0 1 16 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
