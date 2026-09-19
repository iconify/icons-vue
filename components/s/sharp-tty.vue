<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhbankf-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-tty" /></template>
<style>
.qhbankf-f {
  fill: currentColor;
  d: path("M20 15v6c-3.28 0-6.35-.89-9-2.43A18 18 0 0 1 4.43 12A17.85 17.85 0 0 1 2 3h6l1 5l-2.9 2.9c1.43 2.5 3.5 4.57 6 6L15 14zm-6-9h2V4h-2zm-1 3h2V7h-2zm-2-3h2V4h-2zm7 1h-2v2h2zm1-3h-2v2h2zm2 3h-2v2h2zm1-3h-2v2h2zm-8 8h2v-2h-2zm-3 0h2v-2h-2zm8-2h-2v2h2zm3 0h-2v2h2z");
}

</style>
