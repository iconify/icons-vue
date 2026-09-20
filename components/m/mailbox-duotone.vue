<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="lra5z_bey"/><path class="u2cu26b7n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:mailbox-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lra5z_bey {
  d: path("M232 116v60a8 8 0 0 1-8 8h-96v-68a52 52 0 0 0-52-52h104a52 52 0 0 1 52 52");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u2cu26b7n {
  d: path("M104 152a8 8 0 0 1-8 8H56a8 8 0 0 1 0-16h40a8 8 0 0 1 8 8m136-36v60a16 16 0 0 1-16 16h-88v32a8 8 0 0 1-16 0v-32H32a16 16 0 0 1-16-16v-60a60.07 60.07 0 0 1 60-60h76V24a8 8 0 0 1 8-8h32a8 8 0 0 1 0 16h-24v24h12a60.07 60.07 0 0 1 60 60m-120 60v-60a44 44 0 0 0-88 0v60Zm104-60a44.05 44.05 0 0 0-44-44h-12v72a8 8 0 0 1-16 0V72h-35.25A59.86 59.86 0 0 1 136 116v60h88Z");
}

</style>
