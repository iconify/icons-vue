<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8d4skb4e"/><path class="f2ui0_bkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-width-wide" /></template>
<style>
.f2ui0_bkf {
  fill: currentColor;
  d: path("M20 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2M6 18H4V6h2zm10 0H8V6h8zm4 0h-2V6h2z");
}

.o8d4skb4e {
  fill: currentColor;
  d: path("M8 6h8v12H8z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
