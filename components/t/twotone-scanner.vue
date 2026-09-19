<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3p3f5byp"/><path class="m2ppizb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-scanner" /></template>
<style>
.f3p3f5byp {
  fill: currentColor;
  d: path("M5 14v4h14v-4zm3 3H6v-2h2zm10 0h-8v-2h8z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.m2ppizb7d {
  fill: currentColor;
  d: path("M19.8 10.7L4.2 5l-.7 1.9L17.6 12H5c-1.1 0-2 .9-2 2v4c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2v-5.5c0-.8-.5-1.6-1.2-1.8M19 18H5v-4h14zM6 15h2v2H6zm4 0h8v2h-8z");
}

</style>
