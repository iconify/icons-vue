<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="oyjujgd1y"/><path class="vdgi0qbsj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wallet-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.oyjujgd1y {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 2L15 2C17.2091 2 19 3.7909 19 6L19 6.127C20.7661 6.583 22 8.176 22 10L22 18C22 20.2091 20.2091 22 18 22L6 22C3.7909 22 2 20.2091 2 18L2 5C2 3.3431 3.3431 2 5 2Z");
}

.vdgi0qbsj {
  d: path("M5 4C4.4477 4 4 4.4477 4 5C4 5.5523 4.4477 6 5 6L17 6C17 4.8954 16.1046 4 15 4L5 4ZM18 12C16.8954 12 16 12.8954 16 14C16 15.1046 16.8954 16 18 16L20 16L20 12L18 12Z");
}

</style>
