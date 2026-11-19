<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ao93qmb2o"/><path class="znrcvfb6l"/><path class="p-wqsbzwk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rabet" /></template>
<style>
.ao93qmb2o {
  fill: var(--svg-color--b8bac4, #b8bac4);
  d: path("M12 20.784c-.437.264-1.003.3-1.492.03l-1.283-.71a2.71 2.71 0 0 1-1.05-3.7L9.42 14.19l1.94 5.792c.117.353.351.628.64.802m4.231-11.528L14.58 14.19l-2.578-4.58l3.61-6.417a.375.375 0 0 1 .7.145l.28 2.616a7.8 7.8 0 0 1-.36 3.302");
}

.ft5dv1b6b {
  fill: none;
}

.p-wqsbzwk {
  fill: var(--svg-color--b8bac4, #b8bac4);
  d: path("M12 9.608L9.42 14.19L7.77 9.256a7.8 7.8 0 0 1-.36-3.302l.28-2.617a.375.375 0 0 1 .7-.145Zm2.774 10.496l-1.28.71a1.49 1.49 0 0 1-1.493-.03c.29-.175.522-.45.64-.801l1.938-5.793l1.246 2.213a2.71 2.71 0 0 1-1.05 3.701");
}

.znrcvfb6l {
  fill: var(--svg-color--000, #000);
  d: path("m14.58 14.19l-1.94 5.792c-.117.351-.35.627-.64.802a1.46 1.46 0 0 1-.64-.801L9.42 14.19L12 9.608z");
}

</style>
