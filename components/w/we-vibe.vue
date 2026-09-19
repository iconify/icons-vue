<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pwkc16b_e"/><path class="w51hwn7vr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:we-vibe" /></template>
<style>
.pwkc16b_e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m43.5 19.467l-5.987 9.066l-5.987-9.066m-15.736 0l-2.823 9.066l-2.822-9.066l-2.823 9.066L4.5 19.467");
}

.w51hwn7vr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.309 12.44c9.041 0 11.775 1.488 17.59 11.56s8.55 11.56 17.59 11.56");
}

</style>
