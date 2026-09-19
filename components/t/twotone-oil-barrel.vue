<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="um6-bmbtf"/><path class="vosakharg"/><path class="f1t3f6onl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-oil-barrel" /></template>
<style>
.f1t3f6onl {
  fill: currentColor;
  d: path("M20 13c.55 0 1-.45 1-1s-.45-1-1-1h-1V5h1c.55 0 1-.45 1-1s-.45-1-1-1H4c-.55 0-1 .45-1 1s.45 1 1 1h1v6H4c-.55 0-1 .45-1 1s.45 1 1 1h1v6H4c-.55 0-1 .45-1 1s.45 1 1 1h16c.55 0 1-.45 1-1s-.45-1-1-1h-1v-6zm-3-2c-.55 0-1 .45-1 1s.45 1 1 1v6H7v-6c.55 0 1-.45 1-1s-.45-1-1-1V5h10z");
}

.um6-bmbtf {
  fill: currentColor;
  d: path("M7 11c.55 0 1 .45 1 1s-.45 1-1 1v6h10v-6c-.55 0-1-.45-1-1s.45-1 1-1V5H7zm5-2.5c2.47 2.86 3 3.24 3 4.55c0 1.63-1.34 2.95-3 2.95s-3-1.32-3-2.95c0-1.3.52-1.67 3-4.55");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.vosakharg {
  fill: currentColor;
  d: path("M12 16c1.66 0 3-1.32 3-2.95c0-1.31-.53-1.69-3-4.55c-2.48 2.88-3 3.25-3 4.55C9 14.68 10.34 16 12 16");
}

</style>
