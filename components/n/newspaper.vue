<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="dd7pwgnxn"/><path class="v2hz_n1lk"/><path class="vxnhnrrjm"/><path class="hofqf0blc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:newspaper" /></template>
<style>
.dd7pwgnxn {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M33 36H4c4 0 3-9 3-9c0-2.209 1.791-15 4-15h21s4 0 4 4v17s0 3-3 3");
}

.hofqf0blc {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M13 21s2 0 2-2v-6s0-2-2-2H5s-2 0-2 2v6s0 2 2 2z");
}

.v2hz_n1lk {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M30 33c0 3 3 3 3 3H3s-3 0-3-4V4a4 4 0 0 1 4-4h22a4 4 0 0 1 4 4z");
}

.vxnhnrrjm {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M27 20a1 1 0 0 1-1 1h-8a1 1 0 1 1 0-2h8a1 1 0 0 1 1 1m0-4a1 1 0 0 1-1 1h-8a1 1 0 1 1 0-2h8a1 1 0 0 1 1 1m0-4a1 1 0 0 1-1 1h-8a1 1 0 1 1 0-2h8a1 1 0 0 1 1 1m0 12a1 1 0 0 1-1 1H4a1 1 0 1 1 0-2h22a1 1 0 0 1 1 1m0 4a1 1 0 0 1-1 1H4a1 1 0 1 1 0-2h22a1 1 0 0 1 1 1m0 4a1 1 0 0 1-1 1H4a1 1 0 1 1 0-2h22a1 1 0 0 1 1 1M25 9s2 0 2-2V5s0-2-2-2H5S3 3 3 5v2s0 2 2 2z");
}

</style>
