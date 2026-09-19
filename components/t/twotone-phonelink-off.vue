<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pve7hpfmh"/><path class="k3rdah64f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-phonelink-off" /></template>
<style>
.k3rdah64f {
  fill: currentColor;
  d: path("M23 8h-6c-.55 0-1 .45-1 1v3.61l2 2V10h4v7h-1.61l2.93 2.93c.39-.13.68-.49.68-.93V9c0-.55-.45-1-1-1m-1-2V4H7.39l2 2zM.65 2.92l1.82 1.82C2.18 5.08 2 5.52 2 6v11H0v3h17.73l2.35 2.35l1.41-1.41L2.06 1.51zM4 6.27L14.73 17H4z");
}

.pve7hpfmh {
  fill: currentColor;
  d: path("M22 17v-7h-4v4.61L20.39 17z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
