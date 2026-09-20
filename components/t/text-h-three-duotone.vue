<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="mfyo8rb6u"/><path class="ugqiw7bds"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:text-h-three-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mfyo8rb6u {
  d: path("M240 72v120a16 16 0 0 1-16 16H56a16 16 0 0 1-16-16V56h184a16 16 0 0 1 16 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ugqiw7bds {
  d: path("M152 56v120a8 8 0 0 1-16 0v-52H48v52a8 8 0 0 1-16 0V56a8 8 0 0 1 16 0v52h88V56a8 8 0 0 1 16 0m73.52 90.63l21-30A8 8 0 0 0 240 104h-48a8 8 0 0 0 0 16h32.63l-19.18 27.41A8 8 0 0 0 212 160a20 20 0 1 1-14.29 34a8 8 0 1 0-11.42 11.19A36 36 0 0 0 248 180a36.07 36.07 0 0 0-22.48-33.37");
}

</style>
