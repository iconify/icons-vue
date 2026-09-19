<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scp43bbsy"/><path class="izr474x_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-thumb-up-off-alt" /></template>
<style>
.izr474x_j {
  fill: currentColor;
  d: path("M21 8h-6.31l.95-4.57l.03-.32c0-.41-.17-.79-.44-1.06L14.17 1L7.59 7.59C7.22 7.95 7 8.45 7 9v10c0 1.1.9 2 2 2h9c.83 0 1.54-.5 1.84-1.22l3.02-7.05c.09-.23.14-.47.14-.73v-2c0-1.1-.9-2-2-2m0 4l-3 7H9V9l4.34-4.34L12.23 10H21zM1 9h4v12H1z");
}

.scp43bbsy {
  fill: currentColor;
  d: path("M13.34 4.66L9 9v10h9l3-7v-2h-8.77z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
