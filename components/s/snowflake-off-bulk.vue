<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="scct2ub4e"/><path class="ploctgb1y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:snowflake-off-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ploctgb1y {
  d: path("M11 3a1 1 0 0 1 2 0v4.5a1 1 0 0 1-2 0Zm8.294 3.634a1 1 0 0 1 1 1.732l-5.258 3.036a1 1 0 0 1-1-1.732ZM3.706 8.366a1 1 0 1 1 1-1.732l3.062 1.768a1 1 0 0 1-1 1.732Zm7.338 5.341l-6.338 3.659a1 1 0 0 1-1-1.732l6.526-3.768a1 1 0 0 1 1.447 1.187A1.002 1.002 0 0 1 13 14v7a1 1 0 0 1-2 0v-7q0-.15.044-.293");
}

.scct2ub4e {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m8.532 9.117l12.175 12.176a.999.999 0 1 1-1.414 1.414l-4.297-4.297a1.001 1.001 0 0 1-1.703.797L12 17.914l-1.293 1.293a.999.999 0 1 1-1.414-1.414l2-2a1 1 0 0 1 .797-.289L7.526 10.94l-1.896.508a1 1 0 0 1-.518-1.932l.781-.209l-4.6-4.6a.999.999 0 1 1 1.414-1.414Zm.761-2.91a.999.999 0 1 1 1.414-1.414L12 6.086l1.293-1.293a.999.999 0 1 1 1.414 1.414l-2 2a1 1 0 0 1-1.414 0Zm6.37.552a1 1 0 0 1 1.932.518l-.473 1.766l1.766.473a1 1 0 0 1-.518 1.932l-2.732-.732a1 1 0 0 1-.707-1.225Zm-6.594 7.75l-.732 2.732a1 1 0 0 1-1.932-.518l.473-1.766l-1.766-.473a1 1 0 0 1 .518-1.932l2.731.732h.001a1 1 0 0 1 .707 1.225");
}

</style>
