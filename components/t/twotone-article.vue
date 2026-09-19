<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f87q51b3k"/><path class="xt3-er4en"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-article" /></template>
<style>
.f87q51b3k {
  fill: currentColor;
  d: path("M5 5v14h14V5zm9 12H7v-2h7zm3-4H7v-2h10zm0-4H7V7h10z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.xt3-er4en {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H5V5h14zm-2-6H7v-2h10zm0-4H7V7h10zm-3 8H7v-2h7z");
}

</style>
