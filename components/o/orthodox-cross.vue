<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="dgh7jhswh"/><path class="apbt12bic"/><path class="eph873b2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:orthodox-cross" /></template>
<style>
.apbt12bic {
  fill: var(--svg-color--fff, #fff);
  d: path("M23 6h-3V4a1 1 0 0 0-1-1h-2a1 1 0 0 0-1 1v2h-3a1 1 0 0 0-1 1v2a1 1 0 0 0 1 1h3v22a1 1 0 0 0 1 1h2a1 1 0 0 0 1-1V10h3a1 1 0 0 0 1-1V7a1 1 0 0 0-1-1");
}

.dgh7jhswh {
  fill: var(--svg-color--9266cc, #9266cc);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

.eph873b2y {
  fill: var(--svg-color--fff, #fff);
  d: path("M29 13H7a1 1 0 0 0-1 1v2a1 1 0 0 0 1 1h22a1 1 0 0 0 1-1v-2a1 1 0 0 0-1-1m-4.676 11.924l-11.429-3.657a1 1 0 0 0-1.257.648l-.61 1.905a1 1 0 0 0 .648 1.257l11.429 3.657a1 1 0 0 0 1.257-.648l.61-1.905a1 1 0 0 0-.648-1.257");
}

</style>
