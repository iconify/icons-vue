<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajskkm76x"/><path class="xb1wc2b7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-center-focus-weak" /></template>
<style>
.ajskkm76x {
  fill: currentColor;
  d: path("M12 10c-1.1 0-2 .9-2 2s.9 2 2 2s2-.9 2-2s-.9-2-2-2");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.xb1wc2b7r {
  fill: currentColor;
  d: path("M3 19c0 1.1.9 2 2 2h4v-2H5v-4H3zM3 5v4h2V5h4V3H5c-1.1 0-2 .9-2 2m9 3c-2.21 0-4 1.79-4 4s1.79 4 4 4s4-1.79 4-4s-1.79-4-4-4m0 6c-1.1 0-2-.9-2-2s.9-2 2-2s2 .9 2 2s-.9 2-2 2m9-9c0-1.1-.9-2-2-2h-4v2h4v4h2zm-2 14h-4v2h4c1.1 0 2-.9 2-2v-4h-2z");
}

</style>
