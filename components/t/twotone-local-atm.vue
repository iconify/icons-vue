<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzo6zobix"/><path class="rr64_ibsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-local-atm" /></template>
<style>
.rr64_ibsb {
  fill: currentColor;
  d: path("M20 4H4c-1.11 0-1.99.89-1.99 2L2 18c0 1.11.89 2 2 2h16c1.11 0 2-.89 2-2V6c0-1.11-.89-2-2-2m0 14H4V6h16zm-9-1h2v-1h1c.55 0 1-.45 1-1v-3c0-.55-.45-1-1-1h-3v-1h4V8h-2V7h-2v1h-1c-.55 0-1 .45-1 1v3c0 .55.45 1 1 1h3v1H9v2h2z");
}

.rzo6zobix {
  fill: currentColor;
  d: path("M4 18h16V6H4zm5-4h4v-1h-3c-.55 0-1-.45-1-1V9c0-.55.45-1 1-1h1V7h2v1h2v2h-4v1h3c.55 0 1 .45 1 1v3c0 .55-.45 1-1 1h-1v1h-2v-1H9z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
