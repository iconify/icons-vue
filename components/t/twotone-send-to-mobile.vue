<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="be625c6pp"/><path class="d7-8-q3yy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-send-to-mobile" /></template>
<style>
.be625c6pp {
  fill: currentColor;
  d: path("M7 3h10v1H7zm0 17h10v1H7z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.d7-8-q3yy {
  fill: currentColor;
  d: path("m22 12l-4-4v3h-5v2h5v3zm-5 6H7V6h10v1h2V3c0-1.1-.9-2-2-2L7 1.01C5.9 1.01 5 1.9 5 3v18c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2v-4h-2zM7 3h10v1H7zm10 18H7v-1h10z");
}

</style>
