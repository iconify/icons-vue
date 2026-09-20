<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="w502f1bnz"/><path class="uem734bop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:pen" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.uem734bop {
  d: path("m11.442 5.247l1.06-1.061l3.242 3.24l-1.061 1.061z");
}

.w502f1bnz {
  fill-rule: evenodd;
  d: path("M13.198 1.22L3.12 11.298a1 1 0 0 0-.282.555l-.705 4.594a1 1 0 0 0 1.14 1.14l4.595-.705a1 1 0 0 0 .555-.281L18.501 6.523a1 1 0 0 0 0-1.414l-3.89-3.89a1 1 0 0 0-1.413 0M4.317 15.404l.448-2.924l9.14-9.14l2.475 2.476l-9.14 9.14z");
}

</style>
