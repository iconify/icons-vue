<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rh7i28bws"/><path class="d_646lw6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-brush" /></template>
<style>
.d_646lw6x {
  fill: currentColor;
  d: path("m11.75 15l8.96-8.96a.996.996 0 0 0 0-1.41l-1.34-1.34c-.2-.2-.45-.29-.7-.29s-.51.1-.71.29L9 12.25zM6 21c2.21 0 4-1.79 4-4c0-1.66-1.34-3-3-3s-3 1.34-3 3c0 1.31-1.16 2-2 2c.92 1.22 2.49 2 4 2m0-4c0-.55.45-1 1-1s1 .45 1 1c0 1.1-.9 2-2 2c-.17 0-.33-.02-.5-.05c.31-.55.5-1.21.5-1.95");
}

.rh7i28bws {
  fill: currentColor;
  d: path("M8 17c0-.55-.45-1-1-1s-1 .45-1 1c0 .74-.19 1.4-.5 1.95c.17.03.33.05.5.05c1.1 0 2-.9 2-2");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
