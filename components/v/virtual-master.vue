<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kc9aqtmoq"/><path class="xv5i6pb9e"/><path class="h157wabyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:virtual-master" /></template>
<style>
.h157wabyj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.593 5.5l-12.594 7.423L11.407 5.5");
}

.kc9aqtmoq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.585 22.557v13.837L23.999 42.5l-10.583-6.106V22.557");
}

.xv5i6pb9e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.62 32.7V11.278L24 21.343L7.379 11.28V32.7");
}

</style>
