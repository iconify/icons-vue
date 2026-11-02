<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nb5ze6jpe"/><path class="lno3zub7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:taxi-side-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lno3zub7e {
  d: path("M12 5H9a1 1 0 0 1 0-2h3a1 1 0 0 1 0 2M4 18a3 3 0 1 1 6 0a3 3 0 0 1-6 0m10 0a3 3 0 1 1 6 0a3 3 0 0 1-6 0m-8 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0m10 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

.nb5ze6jpe {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6.293 7.293C7.252 6.335 8.683 6 10 6h1c1.317 0 2.748.335 3.707 1.293L18.414 11H19a3 3 0 0 1 3 3v2c0 1.32-.866 2.487-2.128 2.872a3.002 3.002 0 0 1-5.701.128H9.829a3 3 0 0 1-5.701-.128A3.01 3.01 0 0 1 2 16v-4c0-.265.105-.52.293-.707ZM9 8.073Q9.325 8 9.657 8H9Zm-1.462.803L4 12.414V13h5V8.073a3 3 0 0 0-1.462.803M11 13h6.586l-.291-.291l-.002-.002l-3.831-3.831A3 3 0 0 0 11.343 8H11Zm-4.709 5.705l.002.002l.002.002a1 1 0 0 0 1.41 0l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 0 1.41m11.414.004l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 1.414 1.414");
}

</style>
