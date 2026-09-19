<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0_4e5byz"/><path class="eqzu9um-d"/><path class="juft94bgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-price-change" /></template>
<style>
.eqzu9um-d {
  fill: currentColor;
  d: path("M20 4H4c-1.11 0-1.99.89-1.99 2L2 18c0 1.11.89 2 2 2h16c1.11 0 2-.89 2-2V6c0-1.11-.89-2-2-2m0 14H4V6h16z");
}

.juft94bgu {
  fill: currentColor;
  d: path("M8 17h2v-1h1c.55 0 1-.45 1-1v-3c0-.55-.45-1-1-1H8v-1h4V8h-2V7H8v1H7c-.55 0-1 .45-1 1v3c0 .55.45 1 1 1h3v1H6v2h2zm8-9l-2 2h4zm2 6.25h-4l2 2z");
}

.n0_4e5byz {
  fill: currentColor;
  d: path("M4 18h16V6H4zM16 8l2 2h-4zm2 6.25l-2 2l-2-2zM6 14h4v-1H7c-.55 0-1-.45-1-1V9c0-.55.45-1 1-1h1V7h2v1h2v2H8v1h3c.55 0 1 .45 1 1v3c0 .55-.45 1-1 1h-1v1H8v-1H6z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
