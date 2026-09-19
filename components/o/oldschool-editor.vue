<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gqzutib3e"/><path class="y5nd7v_zw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:oldschool-editor" /></template>
<style>
.gqzutib3e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.645 7.343H42.5l-12.145 24.66H5.5z");
}

.y5nd7v_zw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.467 7.353v33.304H18.063V31.98m21.396 5.121l-18.442.004zm-18.442-2.706l18.443.004zm9.573-2.705l8.87.003zm1.352-2.706l7.518.004zm1.353-2.706l6.165.004zm1.353-2.705l4.812.003zM36 20.867l3.46.003zm1.354-2.706l2.106.004zm2.106-2.702h-.85");
}

</style>
