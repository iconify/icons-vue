<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="oq90vzbhr"/><path class="popaz21gp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:star-off-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.oq90vzbhr {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18.328 15.086L9.336 6.093l1.77-3.54a.998.998 0 0 1 1.788 0l2.766 5.531l6.481.926a1.001 1.001 0 0 1 .566 1.697ZM17.6 18.6l1.217 1.217l.169 1.019a1 1 0 0 1-.392.968a1 1 0 0 1-1.041.09L12 19.118l-5.553 2.776a1 1 0 0 1-1.041-.09a1 1 0 0 1-.392-.968l.915-5.493l-4.636-4.636a1.001 1.001 0 0 1 .566-1.697l5.382-.769Z");
}

.popaz21gp {
  d: path("M1.293 3.707a.999.999 0 1 1 1.414-1.414l19 19a.999.999 0 1 1-1.414 1.414Z");
}

</style>
