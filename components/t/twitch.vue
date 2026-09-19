<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jrx0z_zvt"/><path class="t4nig_b2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:twitch" /></template>
<style>
.jrx0z_zvt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.11 4.52l-6.88 6.84v25.12h8.3v7l7.06-7h5.61l12.57-12.46V4.52z");
}

.t4nig_b2t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.53 7.41H38v15.2l-5.45 5.41h-5.61l-5.12 5.13v-5.13h-6.29zm9.175 5.365v6.992m7.69.008v-7");
}

</style>
