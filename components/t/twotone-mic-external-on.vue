<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6bs6_ivh"/><path class="c_u928bnh"/><path class="iu-z93beq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-mic-external-on" /></template>
<style>
.c_u928bnh {
  fill: currentColor;
  d: path("M9.22 7c.48-.53.78-1.23.78-2c0-1.66-1.34-3-3-3S4 3.34 4 5c0 .77.3 1.47.78 2z");
}

.h6bs6_ivh {
  fill: currentColor;
  d: path("M6.81 16h.38l.6-6H6.21z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.iu-z93beq {
  fill: currentColor;
  d: path("M16 2c-2.21 0-4 1.79-4 4v12c0 1.1-.9 2-2 2s-2-.9-2-2h1l1-10H4l1 10h1c0 2.21 1.79 4 4 4s4-1.79 4-4V6c0-1.1.9-2 2-2s2 .9 2 2v16h2V6c0-2.21-1.79-4-4-4M7.19 16h-.38l-.6-6h1.58z");
}

</style>
