<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="wb4cn7pcx"/><path class="lwef9vban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:ycombinator" /></template>
<style>
.lwef9vban {
  fill: var(--svg-color--fff, #fff);
  d: path("M119.374 144.746L75.433 62.432h20.081l25.848 52.092q.597 1.392 1.392 2.883t1.391 3.082q.398.596.597 1.094q.199.496.398.894a66 66 0 0 1 1.79 3.877q.795 1.89 1.39 3.48q1.591-3.381 3.48-7.257q1.89-3.878 3.877-8.053l26.246-52.092h18.69l-44.34 83.308v53.087h-16.9z");
}

.wb4cn7pcx {
  fill: var(--svg-color--fb651e, #fb651e);
  d: path("M0 0h256v256H0z");
}

</style>
