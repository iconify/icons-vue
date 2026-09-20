<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ul1b42ela"/><path class="xedf9ccsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:ruler-off" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ul1b42ela {
  fill-rule: evenodd;
  d: path("M1.25 15.392a2 2 0 0 1 0-2.828L12.564 1.25a2 2 0 0 1 2.828 0l3.536 3.536a2 2 0 0 1 0 2.828L7.614 18.928a2 2 0 0 1-2.828 0zm2.121-2.121l-.707.707L6.2 17.513L17.514 6.2l-3.536-3.536l-.707.707l1.355 1.356a1 1 0 0 1-1.414 1.414l-1.355-1.355l-.707.707l.53.53a1 1 0 0 1-1.414 1.414l-.53-.53l-.708.707l1.355 1.355a1 1 0 1 1-1.414 1.414L7.614 9.028l-.707.707l.53.53a1 1 0 1 1-1.414 1.415l-.53-.53l-.707.707l1.355 1.355a1 1 0 1 1-1.414 1.414z");
}

.xedf9ccsf {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
