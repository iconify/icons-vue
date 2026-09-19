<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bva7oab6q"/><path class="ye1xl3czj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zvuk-business" /></template>
<style>
.bva7oab6q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.535 9.465C41.625 12.555 42.5 19.631 42.5 24c0 4.37-.876 11.446-3.965 14.535S28.369 42.5 24 42.5c-4.37 0-11.446-.876-14.535-3.965S5.5 28.369 5.5 24c0-4.37.876-11.446 3.965-14.535S19.631 5.5 24 5.5c4.37 0 11.446.876 14.535 3.965");
}

.ye1xl3czj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.971 13.921h.1c14.916 0 27.008 12.092 27.008 27.008v.001h0v.1M5.515 24.71q.776-.075 1.556-.074c8.998 0 16.292 7.295 16.293 16.293q0 .778-.074 1.552");
}

</style>
