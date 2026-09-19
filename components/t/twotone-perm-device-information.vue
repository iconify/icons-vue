<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xt493fbfh"/><path class="tsopokftc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-perm-device-information" /></template>
<style>
.tsopokftc {
  fill: currentColor;
  d: path("M11 7h2v2h-2zm0 4h2v6h-2zm6-9.99L7 1c-1.1 0-2 .9-2 2v18c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2V3c0-1.1-.9-1.99-2-1.99M17 21H7v-1h10zm0-3H7V6h10zm0-14H7V3h10z");
}

.xt493fbfh {
  fill: currentColor;
  d: path("M7 20h10v1H7zM7 3h10v1H7z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
