<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zztm5acki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:running-ability" /></template>
<style>
.zztm5acki {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.333 29.34L42.5 40.021m-20.5 0L15.833 29.34h12.5c3.556 0 5.778-3.849 4-6.928L24 7.978L5.5 40.02");
}

</style>
