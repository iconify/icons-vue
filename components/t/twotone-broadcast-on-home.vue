<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wuk0o3ban"/><path class="b89ev1bia"/><path class="wqgw2ubvk"/><path class="hmkkhmb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-broadcast-on-home" /></template>
<style>
.b89ev1bia {
  fill: currentColor;
  d: path("M20 8.59c.73.29 1.4.69 2 1.17V6c0-1.1-.9-2-2-2H4v2h16zM8 9H3c-.5 0-1 .5-1 1v9c0 .5.5 1 1 1h5c.5 0 1-.5 1-1v-9c0-.5-.5-1-1-1m-1 9H4v-7h3zm10-3.25c-.69 0-1.25.56-1.25 1.25c0 .4.2.75.5.97V22h1.5v-5.03c.3-.23.5-.57.5-.97c0-.69-.56-1.25-1.25-1.25");
}

.hmkkhmb9q {
  fill: currentColor;
  d: path("M17 9.5a6.5 6.5 0 0 0-6.5 6.5c0 1.79.73 3.42 1.9 4.6l1.06-1.06C12.56 18.63 12 17.38 12 16c0-2.76 2.24-5 5-5s5 2.24 5 5c0 1.37-.56 2.62-1.46 3.52l1.07 1.06A6.5 6.5 0 0 0 17 9.5");
}

.wqgw2ubvk {
  fill: currentColor;
  d: path("M17 12c-2.21 0-4 1.79-4 4c0 1.1.45 2.1 1.17 2.83l1.06-1.06A2.5 2.5 0 1 1 19.5 16c0 .69-.28 1.31-.73 1.76l1.06 1.06C20.55 18.1 21 17.1 21 16c0-2.21-1.79-4-4-4");
}

.wuk0o3ban {
  fill: currentColor;
  d: path("M4 11h3v7H4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
