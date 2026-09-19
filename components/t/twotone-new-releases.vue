<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlc7hmbqd"/><path class="crw6-ybff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-new-releases" /></template>
<style>
.crw6-ybff {
  fill: currentColor;
  d: path("m20.9 5.54l-3.61-.82l-1.89-3.18L12 3L8.6 1.54L6.71 4.72l-3.61.81l.34 3.68L1 12l2.44 2.78l-.34 3.69l3.61.82l1.89 3.18L12 21l3.4 1.46l1.89-3.18l3.61-.82l-.34-3.68L23 12l-2.44-2.78zM18.75 16.9l-2.74.62l-1.43 2.41L12 18.82l-2.58 1.11l-1.43-2.41l-2.74-.62l.26-2.8L3.66 12l1.85-2.12l-.26-2.78l2.74-.61l1.43-2.41L12 5.18l2.58-1.11l1.43 2.41l2.74.62l-.26 2.79L20.34 12l-1.85 2.11zM11 15h2v2h-2zm0-8h2v6h-2z");
}

.hlc7hmbqd {
  fill: currentColor;
  d: path("m18.49 9.89l.26-2.79l-2.74-.62l-1.43-2.41L12 5.18L9.42 4.07L7.99 6.48l-2.74.62l.26 2.78L3.66 12l1.85 2.11l-.26 2.8l2.74.62l1.43 2.41L12 18.82l2.58 1.11l1.43-2.41l2.74-.62l-.26-2.79L20.34 12zM13 17h-2v-2h2zm0-4h-2V7h2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
