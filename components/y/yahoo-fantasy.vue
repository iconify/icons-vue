<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="crbtt5wsd"/><path class="gsq0tvb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yahoo-fantasy" /></template>
<style>
.crbtt5wsd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.333 17.633c0 6.81-5.522 12.332-12.333 12.332s-12.333-5.521-12.333-12.332V8.59h24.666z");
}

.gsq0tvb_t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.667 12.01H4.5v3.234a9.25 9.25 0 0 0 9.252 9.252m13.199 5.113v3.557h6.094v2.775h3.915v3.469H11.04v-3.469h3.915v-2.775h6.094v-3.557m6.843-21.018v12.932L24 17.867l-3.892 3.656V8.591m16.225 3.419H43.5v3.234a9.25 9.25 0 0 1-9.252 9.252");
}

</style>
