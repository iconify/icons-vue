<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e84vh4nlt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:t-membership" /></template>
<style>
.e84vh4nlt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.902 26.133v5.61m0-15.363v5.487m3.318 4.266v5.61m0-15.363v5.487m3.316 4.266v5.61m0-15.363v5.487m6.444 4.266v5.61m0-15.363v5.487m3.15 4.266v5.61m0-15.363v5.487m3.485 4.266v5.61m0-15.363v5.487m-9.617 4.266v5.61m0-15.363v5.487m14.107 4.266v5.61m0-15.363v5.487m4.024 4.266v5.61m0-15.363v5.487M5.343 24h37.314M5.72 13.087V8.186h4.969m0 31.628h-4.97v-4.901m36.561 0v4.901h-4.969m0-31.628h4.97v4.901");
}

</style>
