<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aibtjkgta"/><path class="ou0c1xbyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-signal-wifi-3-bar" /></template>
<style>
.aibtjkgta {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M23.64 7c-.45-.34-4.93-4-11.64-4C5.28 3 .81 6.66.36 7l10.08 12.56c.8 1 2.32 1 3.12 0z");
}

.ou0c1xbyq {
  fill: currentColor;
  d: path("m3.53 10.95l6.91 8.61c.8 1 2.32 1 3.12 0l6.91-8.61C20.04 10.62 16.81 8 12 8s-8.04 2.62-8.47 2.95");
}

</style>
