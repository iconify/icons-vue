<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rediwmm9f"/><path class="cxr3p0std"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:traficar" /></template>
<style>
.cxr3p0std {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 33.409c-3.432-5.251-6.662-11.68-6.662-16.246c0-3.674 2.988-6.663 6.662-6.663s6.662 2.989 6.662 6.663c0 4.567-3.23 10.995-6.662 16.246");
}

.rediwmm9f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.662 17.162C36.662 10.17 30.993 4.5 24 4.5s-12.662 5.67-12.662 12.662C11.338 28.574 24 43.5 24 43.5s12.662-14.926 12.662-26.338");
}

</style>
