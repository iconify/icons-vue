<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ic7n52b8f"/><path class="xedf9ccsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:triangle-right-off" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ic7n52b8f {
  fill-rule: evenodd;
  d: path("M12.998 10L6 5.963v8.074zm2.5.866a1 1 0 0 0 0-1.732L5.5 3.365a1 1 0 0 0-1.5.866V15.77a1 1 0 0 0 1.5.866z");
}

.xedf9ccsf {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
