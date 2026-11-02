<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u9d8embjt"/><path class="jrgxclcnp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trophy-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jrgxclcnp {
  d: path("M5 8h2a1 1 0 0 1 0 2H5a3.004 3.004 0 0 1-3-2.999V7a3.004 3.004 0 0 1 2.999-3H7a1 1 0 0 1 0 2H5a1 1 0 0 0 0 2m12-2a1 1 0 0 1 0-2h2a3 3 0 0 1 0 6h-2a1 1 0 0 1 0-2h2a1.002 1.002 0 0 0 .866-1.5A1 1 0 0 0 19 6Zm-6 10c0 .625-.214 1.22-.595 1.713c-.297.384-.672.695-1.046 1c-.447.365-.926.746-1.165 1.287h7.612c-.239-.541-.718-.922-1.165-1.287c-.374-.305-.749-.616-1.046-1A2.8 2.8 0 0 1 13 16v-2a1 1 0 0 1 2 0v2c0 .18.069.349.178.491c.201.261.475.466.728.673c.228.186.455.374.669.576q.386.36.69.791c.307.442.522.942.633 1.469H18a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2h.102c.193-.902.661-1.634 1.323-2.26c.214-.202.441-.39.669-.576c.253-.207.527-.412.728-.673A.8.8 0 0 0 9 16v-2a1 1 0 0 1 2 0Z");
}

.u9d8embjt {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 3a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v6a6 6 0 0 1-3 5.198V16c0 .18.069.349.178.491c.201.261.475.466.728.673c.228.186.455.374.669.576q.386.36.69.791c.503.726.735 1.591.735 2.469a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1c0-.878.232-1.743.735-2.469q.304-.431.69-.791c.214-.202.441-.39.669-.576c.253-.207.527-.412.728-.673A.8.8 0 0 0 9 16v-1.802A6 6 0 0 1 6 9Z");
}

</style>
