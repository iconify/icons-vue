<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="arm8knh_k"/><path class="p3cqnsbey"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:microphone-text-bulk-round" /></template>
<style>
.arm8knh_k {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 6a3 3 0 1 1 6 0v6a3 3 0 1 1-6 0Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.p3cqnsbey {
  d: path("M21 6a1 1 0 0 1 0 2h-2v5a1 1 0 0 1-2 0V8h-2a1 1 0 0 1 0-2ZM7.998 16h.004a4.4 4.4 0 0 0 1.499-.255C11.182 15.147 12 13.722 12 12v-2a1 1 0 0 1 2 0v2c0 1.707-.591 3.336-1.898 4.498a5.8 5.8 0 0 1-1.931 1.132q-.571.203-1.171.295V20h3a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2h3v-2.075a6.4 6.4 0 0 1-1.171-.295a5.8 5.8 0 0 1-1.931-1.132C2.592 15.336 2 13.706 2 12v-2a1 1 0 0 1 2 0v2c0 1.723.819 3.148 2.499 3.745c.481.171.988.257 1.499.255");
}

</style>
