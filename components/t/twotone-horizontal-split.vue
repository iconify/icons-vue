<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xla0yzz0p"/><path class="utl6yh7kl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-horizontal-split" /></template>
<style>
.utl6yh7kl {
  fill: currentColor;
  d: path("M5 15h14v2H5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.xla0yzz0p {
  fill: currentColor;
  d: path("M19 15v2H5v-2zm2-10H3v2h18zm0 4H3v2h18zm0 4H3v6h18z");
}

</style>
