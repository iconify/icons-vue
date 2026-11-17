<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="oy7ha3bnr"/><path class="o6xwmgbrg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:window-horizontal-open-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.o6xwmgbrg {
  d: path("M11 13V18H4V13H11ZM11 6V11H4V6H11Z");
}

.oy7ha3bnr {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M21 4C21.552 4 22 4.448 22 5V18H23V20H1V18H2V5C2 4.448 2.448 4 3 4H21ZM13 18H20V6H13V18Z");
}

</style>
