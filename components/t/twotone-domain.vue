<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fm6mpkbdh"/><path class="rnblddb3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-domain" /></template>
<style>
.fm6mpkbdh {
  fill: currentColor;
  d: path("M12 11h2v2h-2v2h2v2h-2v2h8V9h-8zm4 0h2v2h-2zm0 4h2v2h-2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.rnblddb3f {
  fill: currentColor;
  d: path("M12 7V3H2v18h20V7zM6 19H4v-2h2zm0-4H4v-2h2zm0-4H4V9h2zm0-4H4V5h2zm4 12H8v-2h2zm0-4H8v-2h2zm0-4H8V9h2zm0-4H8V5h2zm10 12h-8v-2h2v-2h-2v-2h2v-2h-2V9h8zm-4-8h2v2h-2zm0 4h2v2h-2z");
}

</style>
