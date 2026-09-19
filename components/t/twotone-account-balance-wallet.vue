<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyt3ymb6h"/><path class="rhsr4ubps"/><circle class="xp85f9bzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-account-balance-wallet" /></template>
<style>
.iyt3ymb6h {
  fill: currentColor;
  d: path("M13 17c-1.1 0-2-.9-2-2V9c0-1.1.9-2 2-2h6V5H5v14h14v-2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.rhsr4ubps {
  fill: currentColor;
  d: path("M21 7.28V5c0-1.1-.9-2-2-2H5a2 2 0 0 0-2 2v14a2 2 0 0 0 2 2h14c1.1 0 2-.9 2-2v-2.28A2 2 0 0 0 22 15V9c0-.74-.41-1.38-1-1.72M20 9v6h-7V9zM5 19V5h14v2h-6c-1.1 0-2 .9-2 2v6c0 1.1.9 2 2 2h6v2z");
}

.xp85f9bzt {
  cx: 16px;
  cy: 12px;
  r: 1.5px;
  fill: currentColor;
}

</style>
