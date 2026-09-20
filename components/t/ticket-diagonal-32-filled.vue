<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k5w2aubqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:ticket-diagonal-32-filled" /></template>
<style>
.k5w2aubqh {
  fill: currentColor;
  d: path("M16.489 2.952a3.25 3.25 0 0 1 4.596 0l1.123 1.123c.673.672.504 1.656-.01 2.191a2.5 2.5 0 0 0 3.535 3.535l.104-.092c.515-.41 1.337-.533 1.957-.035l.13.116l1.125 1.126a3.25 3.25 0 0 1 0 4.596l-3.561 3.562l-1.69-1.69a1 1 0 0 0-1.414 1.414l1.69 1.69l-8.562 8.561a3.25 3.25 0 0 1-4.597 0L9.79 27.924c-.671-.672-.504-1.656.011-2.191l.155-.177a2.5 2.5 0 0 0-3.69-3.357c-.535.514-1.52.682-2.191.01l-1.123-1.124a3.25 3.25 0 0 1 0-4.596l8.561-8.562l1.69 1.69a1 1 0 0 0 1.414-1.414l-1.69-1.69zm1.31 8.432a1 1 0 1 0-1.415 1.414l2.819 2.819a1 1 0 0 0 1.413-1.415z");
}

</style>
