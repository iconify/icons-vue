<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zu2_b2bxe"/><path class="lno3zub7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:taxi-side-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lno3zub7e {
  d: path("M12 5H9a1 1 0 0 1 0-2h3a1 1 0 0 1 0 2M4 18a3 3 0 1 1 6 0a3 3 0 0 1-6 0m10 0a3 3 0 1 1 6 0a3 3 0 0 1-6 0m-8 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0m10 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

.zu2_b2bxe {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6.293 7.293C7.008 6.578 7.961 6 9 6h3c1.039 0 1.992.578 2.707 1.293L18.414 11H19a3 3 0 0 1 3 3v2c0 1.32-.866 2.487-2.128 2.872a3.002 3.002 0 0 1-5.701.128H9.829a3 3 0 0 1-5.701-.128A3.01 3.01 0 0 1 2 16v-4c0-.265.105-.52.293-.707ZM9 13V8h-.172a1 1 0 0 0-.707.293L4 12.414V13Zm2 0h6.586l-4.707-4.707A1 1 0 0 0 12.172 8H11Zm-4.709 5.705l.002.002l.002.002a1 1 0 0 0 1.41 0l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 0 1.41m11.414.004l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 1.414 1.414");
}

</style>
