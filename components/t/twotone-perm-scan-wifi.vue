<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1mnzkbah"/><path class="siy1hw4oi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-perm-scan-wifi" /></template>
<style>
.a1mnzkbah {
  fill: currentColor;
  d: path("M12 5c-3.26 0-6.2.85-9.08 2.65L12 18.83l9.08-11.16C18.18 5.85 15.25 5 12 5m1 11h-2v-6h2zm-2-8V6h2v2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.siy1hw4oi {
  fill: currentColor;
  d: path("M12 3C6.95 3 3.15 4.85 0 7.23L12 22L24 7.25C20.85 4.87 17.05 3 12 3M2.92 7.65C5.8 5.85 8.74 5 12 5c3.25 0 6.18.85 9.08 2.67L12 18.83zM11 10h2v6h-2zm0-4h2v2h-2z");
}

</style>
