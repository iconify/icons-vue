<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-6jl3yjx"/><path class="bs5olfb8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-offline-bolt" /></template>
<style>
.bs5olfb8h {
  fill: currentColor;
  d: path("M12 2.02c-5.51 0-9.98 4.47-9.98 9.98s4.47 9.98 9.98 9.98s9.98-4.47 9.98-9.98S17.51 2.02 12 2.02m0 17.96c-4.4 0-7.98-3.58-7.98-7.98S7.6 4.02 12 4.02S19.98 7.6 19.98 12S16.4 19.98 12 19.98M12.75 5l-4.5 8.5h3.14V19l4.36-8.5h-3z");
}

.m-6jl3yjx {
  fill: currentColor;
  d: path("M12 4.02C7.6 4.02 4.02 7.6 4.02 12S7.6 19.98 12 19.98s7.98-3.58 7.98-7.98S16.4 4.02 12 4.02M11.39 19v-5.5H8.25l4.5-8.5v5.5h3z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
