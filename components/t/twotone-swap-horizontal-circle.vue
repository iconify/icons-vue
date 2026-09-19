<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfevnjbgx"/><path class="q0wlfdlws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-swap-horizontal-circle" /></template>
<style>
.pfevnjbgx {
  fill: currentColor;
  d: path("M12 4c-4.41 0-8 3.59-8 8s3.59 8 8 8s8-3.59 8-8s-3.59-8-8-8m1 11H9v2.5L5.5 14L9 10.5V13h4zm2-1.5V11h-4V9h4V6.5l3.5 3.5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.q0wlfdlws {
  fill: currentColor;
  d: path("M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10s10-4.48 10-10S17.52 2 12 2m0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8s8 3.59 8 8s-3.59 8-8 8m3-13.5V9h-4v2h4v2.5l3.5-3.5zm-6 4L5.5 14L9 17.5V15h4v-2H9z");
}

</style>
