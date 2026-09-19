<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ed2dvjbsg"/><path class="kqs4rcmpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:skiff-mail" /></template>
<style>
.ed2dvjbsg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29a4 4 0 0 1 4 4v29a4 4 0 0 1-4 4h-28a5 5 0 0 1-5-5v-28a4 4 0 0 1 4-4");
}

.kqs4rcmpp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.499 13.66L23.97 25L5.5 13.66m.115 7.248l34.303 20.975M42.5 20.85L24.03 32.13");
}

</style>
