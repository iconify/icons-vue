<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ef0e-9bgb"/><path class="t1orw-bnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:thainakarin-connect" /></template>
<style>
.ef0e-9bgb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.434 13.332c-2.558-4.131 5.836-5.961 13.952-2.547c6.577 2.767 19.094 5.381 20.958.602c1.35-3.462-6.586-3.92-11.501 5.053c-4.164 7.6-7.313 17.341-12.743 20.041c-4.61 2.292-12.226-2.687-7.373-6.281");
}

.t1orw-bnb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.81 8.585c-9.334 5.865-12.352 28.74-21.054 30.83M8.348 16.13v3.845H4.504v3.853h3.844v3.842h3.854v-3.842h3.844v-3.853h-3.844V16.13z");
}

</style>
