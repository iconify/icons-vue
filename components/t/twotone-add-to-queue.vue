<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xflbn_xru"/><path class="nd7r3ac0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-add-to-queue" /></template>
<style>
.nd7r3ac0z {
  fill: currentColor;
  d: path("M11 15h2v-3h3v-2h-3V7h-2v3H8v2h3zM21 3H3c-1.11 0-2 .89-2 2v12a2 2 0 0 0 2 2h5v2h8v-2h5c1.1 0 2-.9 2-2V5a2 2 0 0 0-2-2m0 14H3V5h18z");
}

.xflbn_xru {
  fill: currentColor;
  d: path("M3 17h18V5H3zm5-7h3V7h2v3h3v2h-3v3h-2v-3H8z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
