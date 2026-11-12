<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="peq7rmacb"/><path class="oxlegdb9v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mobile-foldable-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.oxlegdb9v {
  d: path("M13 21a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0ZM6.01 6a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Z");
}

.peq7rmacb {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 5v14c0 .446-.296.839-.725.962l-7 2Q14.14 22 14 22h-4q-.14 0-.275-.038l-7-2A1 1 0 0 1 2 19V5c0-.446.296-.839.725-.962l7-2Q9.86 2 10 2h4q.14 0 .275.038l7 2c.429.123.725.516.725.962");
}

</style>
