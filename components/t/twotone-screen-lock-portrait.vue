<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fg4i8jp_r"/><path class="mrkn0sbdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-screen-lock-portrait" /></template>
<style>
.fg4i8jp_r {
  fill: currentColor;
  d: path("M13.2 10c0-.66-.54-1.2-1.2-1.2s-1.2.54-1.2 1.2v1h2.4zM7 19h10V5H7zm2-7c0-.55.45-1 1-1v-1a2 2 0 1 1 4 0v1c.55 0 1 .45 1 1v3c0 .55-.45 1-1 1h-4c-.55 0-1-.45-1-1z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.mrkn0sbdq {
  fill: currentColor;
  d: path("M10 16h4c.55 0 1-.45 1-1v-3c0-.55-.45-1-1-1v-1a2 2 0 1 0-4 0v1c-.55 0-1 .45-1 1v3c0 .55.45 1 1 1m.8-6c0-.66.54-1.2 1.2-1.2s1.2.54 1.2 1.2v1h-2.4zM17 1H7c-1.1 0-2 .9-2 2v18c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2V3c0-1.1-.9-2-2-2m0 18H7V5h10z");
}

</style>
