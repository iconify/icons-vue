<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1bu_vgsn"/><path class="biohh8bqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-headphones-battery" /></template>
<style>
.biohh8bqn {
  fill: currentColor;
  d: path("M21 7h-1V6h-2v1h-1c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h4c.55 0 1-.45 1-1V8c0-.55-.45-1-1-1m-1 9h-2V9h2zM8 6c-3.31 0-6 2.69-6 6v4c0 1.1.9 2 2 2h2v-5H3.5v-1c0-2.48 2.02-4.5 4.5-4.5s4.5 2.02 4.5 4.5v1H10v5h2c1.1 0 2-.9 2-2v-4c0-3.31-2.69-6-6-6");
}

.e1bu_vgsn {
  fill: currentColor;
  d: path("M18 9h2v7h-2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
