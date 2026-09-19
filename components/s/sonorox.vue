<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nuunscc6v"/><path class="xgvp2lbwn"/><path class="vob88bcyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sonorox" /></template>
<style>
.nuunscc6v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.62 7.6l-2.2-4.1h-4.84l-2.2 4.1l2.2 4.1h4.84Zm-7.04 4.1l-2.2-4.1h-4.84l-2.2 4.1l2.2 4.1h4.84Zm-7.04 4.1l-2.2-4.1H7.5l-2.2 4.1l2.2 4.1h4.84Zm0 8.2l-2.2-4.1H7.5L5.3 24l2.2 4.1h4.84Zm0 8.2l-2.2-4.1H7.5l-2.2 4.1l2.2 4.1h4.84Z");
}

.vob88bcyk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.66 36.3l-2.2-4.1h-4.84l-2.2 4.1l2.2 4.1h4.84Zm7.04-20.5l-2.2-4.1h-4.84l-2.2 4.1l2.2 4.1h4.84Zm0 8.2l-2.2-4.1h-4.84l-2.2 4.1l2.2 4.1h4.84Zm-7.04-12.3l-2.2-4.1h-4.84l-2.2 4.1l2.2 4.1h4.84Z");
}

.xgvp2lbwn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.58 36.3l-2.2-4.1h-4.84l-2.2 4.1l2.2 4.1h4.84Zm7.04 4.1l-2.2-4.1h-4.84l-2.2 4.1l2.2 4.1h4.84Zm14.08-8.2l-2.2-4.1h-4.84l-2.2 4.1l2.2 4.1h4.84Z");
}

</style>
