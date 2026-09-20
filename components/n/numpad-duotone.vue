<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="zhblb_2yi"/><path class="h6xp9gdtm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:numpad-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.h6xp9gdtm {
  d: path("M80 48a16 16 0 1 1-16-16a16 16 0 0 1 16 16m48-16a16 16 0 1 0 16 16a16 16 0 0 0-16-16m64 32a16 16 0 1 0-16-16a16 16 0 0 0 16 16M64 88a16 16 0 1 0 16 16a16 16 0 0 0-16-16m64 0a16 16 0 1 0 16 16a16 16 0 0 0-16-16m64 0a16 16 0 1 0 16 16a16 16 0 0 0-16-16M64 144a16 16 0 1 0 16 16a16 16 0 0 0-16-16m64 0a16 16 0 1 0 16 16a16 16 0 0 0-16-16m0 56a16 16 0 1 0 16 16a16 16 0 0 0-16-16m64-56a16 16 0 1 0 16 16a16 16 0 0 0-16-16");
}

.zhblb_2yi {
  d: path("M192 48v152a16 16 0 0 1-16 16H80a16 16 0 0 1-16-16V48Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
