<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b5ptq0brn"/><path class="jsw9msh-x"/><path class="tx-nnczgx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:window-horizontal-sharp-duotone" /></template>
<style>
.b5ptq0brn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 4C21.552 4 22 4.448 22 5V18H23V20H1V18H2V5C2 4.448 2.448 4 3 4H21Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.jsw9msh-x {
  d: path("M11 18H4V13H11V18ZM20 13V18H13V13H20ZM11 11H4V6H11V11Z");
}

.tx-nnczgx {
  d: path("M20 11H13V6H20V11Z");
}

</style>
