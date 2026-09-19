<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6d1qiwsi"/><path class="u9unycbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-remove-from-queue" /></template>
<style>
.k6d1qiwsi {
  fill: currentColor;
  d: path("M3 17h18V5H3zm5-7h8v2H8z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.u9unycbra {
  fill: currentColor;
  d: path("M21 3H3c-1.11 0-2 .89-2 2v12a2 2 0 0 0 2 2h5v2h8v-2h5c1.1 0 2-.9 2-2V5a2 2 0 0 0-2-2m0 14H3V5h18zM8 10h8v2H8z");
}

</style>
