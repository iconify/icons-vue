<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="oh_qu5s9o"/><path class="zs880gbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:miro-icon" /></template>
<style>
.oh_qu5s9o {
  fill: var(--svg-color--fd3, #fd3);
  d: path("M0 64C0 28.654 28.654 0 64 0h128c35.346 0 64 28.654 64 64v128c0 35.346-28.654 64-64 64H64c-35.346 0-64-28.654-64-64z");
}

.zs880gbnc {
  d: path("M170.195 48.8h-23.239l19.366 34.026L123.717 48.8h-23.239l21.303 41.588L77.239 48.8H54l23.239 52.937L54 207.6h23.239l44.542-113.426L100.478 207.6h23.239l42.605-120.988L146.956 207.6h23.239L212.8 75.263z");
}

</style>
