<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2rgxjilx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:notification-audio-sharp" /></template>
<style>
.i2rgxjilx {
  fill: currentColor;
  d: path("M11.997 21.385q-.668 0-1.14-.475q-.472-.474-.472-1.14h3.23q0 .67-.475 1.143q-.476.472-1.143.472M19 18.769H5v-1h1.616V9.846q0-1.96 1.24-3.447T11 4.546V3h2v1.552q.556.106 1.062.317t.942.504q-1.383.546-2.251 1.791T11.885 10q0 2.075 1.462 3.538T16.885 15q.137 0 .256-.006t.244-.017v2.792H19zm-2.558-6.153V7.385h.885v5.23zm-2.326-1.308V8.692H15v2.616zm4.653 0V8.692h.885v2.616z");
}

</style>
