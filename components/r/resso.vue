<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vwn2g2p8o"/><path class="he9u3dlsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:resso" /></template>
<style>
.he9u3dlsp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.373 41.239L14.72 27.005c-3.287-1.897-7.396.475-7.396 4.27v6.287c0 3.796 4.109 6.168 7.396 4.27");
}

.vwn2g2p8o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.324 31.275v6.287c0 3.796 4.109 6.168 7.396 4.27L38.21 28.27c3.287-1.898 3.287-6.642 0-8.54L14.72 6.168c-3.287-1.898-7.396.474-7.396 4.27v11.789");
}

</style>
