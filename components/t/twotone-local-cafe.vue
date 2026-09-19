<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojd2690ja"/><path class="m_cixygoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-local-cafe" /></template>
<style>
.m_cixygoo {
  fill: currentColor;
  d: path("M2 19h18v2H2zm2-6c0 2.21 1.79 4 4 4h6c2.21 0 4-1.79 4-4v-3h2c1.11 0 2-.89 2-2V5c0-1.11-.89-2-2-2H4zm14-8h2v3h-2zM6 5h10v8c0 1.1-.9 2-2 2H8c-1.1 0-2-.9-2-2z");
}

.ojd2690ja {
  fill: currentColor;
  d: path("M8 15h6c1.1 0 2-.9 2-2V5H6v8c0 1.1.9 2 2 2");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
