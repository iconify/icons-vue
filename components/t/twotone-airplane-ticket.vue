<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxfzcob8l"/><path class="jie13nb9z"/><path class="i2_y92b7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-airplane-ticket" /></template>
<style>
.fxfzcob8l {
  fill: currentColor;
  d: path("M4.01 8.54C5.2 9.23 6 10.52 6 12c0 1.47-.81 2.77-2 3.46V18h16V6H4zm4.13 3.99l1.26.99l2.39-.64l-2.4-4.16l1.4-.38l4.01 3.74l2.44-.65a.967.967 0 0 1 1.18.68a.99.99 0 0 1-.69 1.19l-8.86 2.36l-1.66-2.88z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.i2_y92b7u {
  fill: currentColor;
  d: path("M17.73 13.3c.52-.15.82-.68.69-1.19a.967.967 0 0 0-1.18-.68l-2.44.65l-4.01-3.74l-1.4.38l2.4 4.16l-2.39.64l-1.26-.99l-.93.25l1.66 2.88z");
}

.jie13nb9z {
  fill: currentColor;
  d: path("M20.19 4H4c-1.1 0-1.99.9-1.99 2v4c1.1 0 1.99.9 1.99 2s-.89 2-2 2v4c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.81-2-1.81-2M20 18H4v-2.54c1.19-.69 2-1.99 2-3.46c0-1.48-.8-2.77-1.99-3.46L4 6h16z");
}

</style>
