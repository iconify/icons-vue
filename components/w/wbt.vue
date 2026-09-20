<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG9Y6ePdWR)" clip-rule="evenodd" class="o18mvjbiv"/><defs><linearGradient id="SVG9Y6ePdWR" x1="2.995" x2="21" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="kgzmqdb7y"/><stop offset="1" class="zs5f5vaqg"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:wbt" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kgzmqdb7y {
  stop-color: var(--svg-color--e9c570, #e9c570);
}

.o18mvjbiv {
  fill-rule: evenodd;
  d: path("M18.364 18.364A9 9 0 1 1 5.636 5.636a9 9 0 0 1 12.728 12.728M12.42 9.321c.178.076.334.197.45.352h-.005l1.378 1.802l2.809-6.922a9 9 0 0 1 1.733 1.537l-3.244 7.993a1.09 1.09 0 0 1-1.433.592a1.1 1.1 0 0 1-.448-.349l-1.373-1.802l-1.808 4.447a1.09 1.09 0 0 1-.959.684h-.053a1.09 1.09 0 0 1-.965-.583L5.97 12.286a1.093 1.093 0 1 1 1.934-1.018l1.437 2.709l1.643-4.055a1.09 1.09 0 0 1 1.437-.6");
}

.zs5f5vaqg {
  stop-color: var(--svg-color--f7b839, #f7b839);
}

</style>
