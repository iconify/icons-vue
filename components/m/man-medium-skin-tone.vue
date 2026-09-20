<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="mn16fzbcc"/><path class="z92x7qavr"/><path class="eb0564b8e"/><path class="e5lx70ldk"/><path class="zvt-hbcsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:man-medium-skin-tone" /></template>
<style>
.e5lx70ldk {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M19 24h-2a1 1 0 1 1 0-2h2a1 1 0 1 1 0 2");
}

.eb0564b8e {
  fill: var(--svg-color--662113, #662113);
  d: path("M13 20a1 1 0 0 1-1-1v-2a1 1 0 0 1 2 0v2a1 1 0 0 1-1 1m10 0a1 1 0 0 1-1-1v-2a1 1 0 1 1 2 0v2a1 1 0 0 1-1 1");
}

.mn16fzbcc {
  fill: var(--svg-color--d5ab88, #d5ab88);
  d: path("M8 19c0 2.209-1.119 4-2.5 4S3 21.209 3 19s1.119-4 2.5-4S8 16.791 8 19m25 0c0 2.209-1.119 4-2.5 4S28 21.209 28 19s1.119-4 2.5-4s2.5 1.791 2.5 4");
}

.z92x7qavr {
  fill: var(--svg-color--d5ab88, #d5ab88);
  d: path("M5 20.562c0-8.526 5.82-15.438 13-15.438s13 6.912 13 15.438S25.18 36 18 36S5 29.088 5 20.562");
}

.zvt-hbcsv {
  fill: var(--svg-color--963b22, #963b22);
  d: path("m25.274 27.038l-3.294-.941c.003-.034.02-.063.02-.097a1 1 0 0 0-1-1h-6a1 1 0 0 0-1 1c0 .034.016.063.019.097l-3.294.941a1 1 0 0 0 .55 1.924l1.931-.552a.99.99 0 0 0-.1 1.037a1 1 0 0 0 1.341.448l1.577-.788a.98.98 0 0 0 .529.788a1.003 1.003 0 0 0 1.342-.448l.105-.211l.105.211a1 1 0 0 0 1.342.448a.98.98 0 0 0 .529-.788l1.576.788a1 1 0 0 0 1.343-.448a.99.99 0 0 0-.1-1.037l1.931.552q.137.038.275.038a1.001 1.001 0 0 0 .273-1.962M18 0c8.615 0 14 6.358 14 11.656s-1.077 7.417-2.154 5.298l-2.153-4.238s-6.462 0-8.615-2.12c0 0 3.23 6.358-3.231 0c0 0 1.077 4.239-5.385-1.06c0 0-3.23 2.12-4.308 7.417C5.855 18.423 4 16.954 4 11.656C4 6.357 8.308 0 18 0");
}

</style>
