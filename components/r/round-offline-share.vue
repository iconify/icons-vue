<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="beckm8s6k"/><path class="m4oialfeb"/><path class="u5p5_bcaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-offline-share" /></template>
<style>
.beckm8s6k {
  fill: currentColor;
  d: path("M5 5c-.55 0-1 .45-1 1v15c0 1.1.9 2 2 2h9c.55 0 1-.45 1-1s-.45-1-1-1H6V6c0-.55-.45-1-1-1");
}

.m4oialfeb {
  fill: currentColor;
  d: path("M18 1h-8c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2V3c0-1.1-.9-2-2-2m0 14h-8V5h8z");
}

.u5p5_bcaw {
  fill: currentColor;
  d: path("M12.5 10.25h2v.54c0 .45.54.67.85.35l1.29-1.29c.2-.2.2-.51 0-.71l-1.29-1.29a.5.5 0 0 0-.85.35v.54H12c-.55 0-1 .45-1 1v1.5c0 .41.34.75.75.75s.75-.34.75-.75z");
}

</style>
