<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqlhzm2ve"/><path class="anjhu2okj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-source" /></template>
<style>
.anjhu2okj {
  fill: currentColor;
  d: path("M20 6h-8l-2-2H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V8c0-1.1-.9-2-2-2m0 12H4V6h5.17l2 2H20zm-2-6H6v-2h12zm-4 4H6v-2h8z");
}

.cqlhzm2ve {
  fill: currentColor;
  d: path("M9.17 6H4v12h16V8h-8.83z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
