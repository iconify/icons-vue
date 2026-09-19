<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6v_9ye9x"/><path class="ea61t7v1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-switch-right" /></template>
<style>
.ea61t7v1f {
  fill: currentColor;
  d: path("M15.5 15.38V8.62L18.88 12zM14 19l7-7l-7-7zm-4 0V5l-7 7z");
}

.m6v_9ye9x {
  fill: currentColor;
  d: path("M15.5 15.38V8.62L18.88 12z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
