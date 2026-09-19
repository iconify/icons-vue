<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xinogb6ow"/><path class="afm71ac4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-credit-card" /></template>
<style>
.afm71ac4v {
  fill: currentColor;
  d: path("M20 4H4c-1.11 0-1.99.89-1.99 2L2 18c0 1.11.89 2 2 2h16c1.11 0 2-.89 2-2V6c0-1.11-.89-2-2-2m0 14H4v-6h16zm0-10H4V6h16z");
}

.xinogb6ow {
  fill: currentColor;
  d: path("M4 12h16v6H4zm0-6h16v2H4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
