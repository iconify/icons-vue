<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="cfyr1qm9x"/><path class="tm0fzoruy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:womens-room" /></template>
<style>
.cfyr1qm9x {
  fill: var(--svg-color--ea596e, #ea596e);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

.tm0fzoruy {
  fill: var(--svg-color--fff, #fff);
  d: path("m26.795 15.727l-7.041-4.4C20.506 10.691 21 9.666 21 8.5C21 6.566 19.656 5 18 5c-1.657 0-3 1.567-3 3.5c0 1.166.494 2.192 1.246 2.828l-7.041 4.4a1.5 1.5 0 1 0 1.59 2.544l4.355-2.722L11 25h3v6.5a1.5 1.5 0 1 0 3 0V25h2v6.5a1.5 1.5 0 0 0 3 0V25h3l-4.15-9.45l4.355 2.722a1.5 1.5 0 1 0 1.59-2.545");
}

</style>
