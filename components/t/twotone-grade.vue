<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7kotac0q"/><path class="v-zfvbbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-grade" /></template>
<style>
.h7kotac0q {
  fill: currentColor;
  d: path("m17.11 10.83l-2.47-.21l-1.2-.1l-.47-1.11L12 7.13l-.97 2.28l-.47 1.11l-1.2.1l-2.47.21l1.88 1.63l.91.79l-.27 1.17l-.57 2.42l2.13-1.28l1.03-.63l1.03.63l2.13 1.28l-.57-2.42l-.27-1.17l.91-.79z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.v-zfvbbda {
  fill: currentColor;
  d: path("m22 9.24l-7.19-.61L12 2L9.19 8.63L2 9.24l5.46 4.73L5.82 21L12 17.27L18.18 21l-1.64-7.03zm-7.41 5.18l.56 2.41l-2.12-1.28l-1.03-.62l-1.03.62l-2.12 1.28l.56-2.41l.27-1.18l-.91-.79l-1.88-1.63l2.47-.21l1.2-.1l.47-1.11l.97-2.27l.97 2.29l.47 1.11l1.2.1l2.47.21l-1.88 1.63l-.91.79z");
}

</style>
