<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkyd5mbyv"/><path class="u65v5juro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-assistant-photo" /></template>
<style>
.u65v5juro {
  fill: currentColor;
  d: path("M7 14h5.6l.4 2h7V6h-5.6L14 4H5v17h2zm0-8h5.36l.4 2H18v6h-3.36l-.4-2H7z");
}

.vkyd5mbyv {
  fill: currentColor;
  d: path("m14.24 12l.4 2H18V8h-5.24l-.4-2H7v6z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
