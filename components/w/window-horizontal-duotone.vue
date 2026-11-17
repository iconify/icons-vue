<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l_dm2wy5a"/><path class="jsw9msh-x"/><path class="tx-nnczgx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:window-horizontal-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jsw9msh-x {
  d: path("M11 18H4V13H11V18ZM20 13V18H13V13H20ZM11 11H4V6H11V11Z");
}

.l_dm2wy5a {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 4C21.105 4 22 4.895 22 6V18C22.552 18 23 18.448 23 19C23 19.552 22.552 20 22 20H2C1.448 20 1 19.552 1 19C1 18.448 1.448 18 2 18V6C2 4.895 2.895 4 4 4H20Z");
}

.tx-nnczgx {
  d: path("M20 11H13V6H20V11Z");
}

</style>
