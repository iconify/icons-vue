<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fqdydbb7x"/><path class="fstsr3e1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:monolith" /></template>
<style>
.fqdydbb7x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.581 43.5l-10.937-6.769V8.137l10.937 6.768zm-10.937-6.769l10.937-6.768");
}

.fstsr3e1c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.644 8.137L21.419 4.5l10.937 6.768v28.595L26.581 43.5m0-28.595l5.775-3.637");
}

</style>
