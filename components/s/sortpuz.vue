<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ip9-4cbqm"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sortpuz" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ip9-4cbqm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.383 17.451v21.172c-.285 3.636-6.83 3.6-7.057.06l.06-21.291l-.777-.957l8.492-.06zm.115-9.201l-12.414 5.867l-.54 1.109l-3.642-7.672l1.279.196l8.07-3.846m-3.633 15.96v21.171c-.285 3.636-6.83 3.601-7.057.06l.06-21.29l-.777-.958l8.492-.06zm-10.765-2.39v21.171c-.285 3.636-6.83 3.601-7.057.06l.06-21.29l-.777-.958l8.492-.06z");
}

</style>
