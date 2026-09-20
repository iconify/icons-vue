<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="oe27r3bdg"/><path class="j32godb7f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:record-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.j32godb7f {
  d: path("M128 24a104 104 0 1 0 104 104A104.11 104.11 0 0 0 128 24m0 192a88 88 0 1 1 88-88a88.1 88.1 0 0 1-88 88m0-160a72 72 0 1 0 72 72a72.08 72.08 0 0 0-72-72m0 128a56 56 0 1 1 56-56a56.06 56.06 0 0 1-56 56");
}

.oe27r3bdg {
  d: path("M192 128a64 64 0 1 1-64-64a64 64 0 0 1 64 64");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
