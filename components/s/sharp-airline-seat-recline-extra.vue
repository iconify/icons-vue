<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xcc_1tlfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-airline-seat-recline-extra" /></template>
<style>
.xcc_1tlfe {
  fill: currentColor;
  d: path("M5.35 5.64c-.9-.64-1.12-1.88-.49-2.79c.63-.9 1.88-1.12 2.79-.49c.9.64 1.12 1.88.49 2.79c-.64.9-1.88 1.12-2.79.49M16 19H6.5L4 7H2l2.85 14H16zm.23-4h-4.88l-1.03-4.1c1.58.89 3.28 1.54 5.15 1.22V9.99c-1.63.31-3.44-.27-4.69-1.25L9.14 7.47c-.23-.18-.49-.3-.76-.38a2.2 2.2 0 0 0-.99-.06h-.02a2.27 2.27 0 0 0-1.84 2.61L7.44 18h9.24l3.82 3l1.5-1.5z");
}

</style>
