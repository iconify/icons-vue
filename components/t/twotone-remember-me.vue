<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p5lguctyv"/><circle class="n31v7nbpe"/><path class="ub4_x-apr"/><path class="p813a4e8s"/><path class="lr7t4fblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-remember-me" /></template>
<style>
.lr7t4fblz {
  fill: currentColor;
  d: path("M12 13c1.66 0 3-1.34 3-3s-1.34-3-3-3s-3 1.34-3 3s1.34 3 3 3m0-4c.55 0 1 .45 1 1s-.45 1-1 1s-1-.45-1-1s.45-1 1-1");
}

.n31v7nbpe {
  cx: 12px;
  cy: 10px;
  r: 1px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-3, 0.3);
}

.p5lguctyv {
  fill: currentColor;
  d: path("M7 20h10v1H7zm0-2.48V18h10v-.48c-1.47-.99-3.22-1.52-5-1.52s-3.53.53-5 1.52");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.p813a4e8s {
  fill: currentColor;
  d: path("M17 1H7c-1.1 0-2 .9-2 2v18c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2V3c0-1.1-.9-2-2-2m0 20H7v-1h10zm0-3H7v-.48c1.47-.99 3.22-1.52 5-1.52s3.53.53 5 1.52zm0-2.79c-1.5-.77-3.2-1.21-5-1.21s-3.5.44-5 1.21V6h10zM17 4H7V3h10z");
}

.ub4_x-apr {
  fill: currentColor;
  d: path("M7 3h10v1H7z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
