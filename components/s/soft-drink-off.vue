<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="q0gnoeblt"/><path class="b3us21vso"/><path class="tj2pypb4o"/><path class="xedf9ccsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:soft-drink-off" /></template>
<style>
.b3us21vso {
  d: path("M9.217 14.72a.75.75 0 0 1-1.434-.44l4-13a.75.75 0 1 1 1.434.44z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.q0gnoeblt {
  fill-rule: evenodd;
  d: path("M13.411 4H6.589a2.502 2.502 0 0 0-2.481 2.803l1.22 10A2.5 2.5 0 0 0 7.809 19h4.385a2.5 2.5 0 0 0 2.481-2.198l1.218-10A2.5 2.5 0 0 0 13.41 4M6.529 6.004L6.589 6h6.822a.5.5 0 0 1 .496.56l-1.217 10a.5.5 0 0 1-.496.44H7.809a.5.5 0 0 1-.496-.44l-1.22-10a.5.5 0 0 1 .436-.556");
}

.tj2pypb4o {
  d: path("M5.5 10.25a.75.75 0 0 1 0-1.5h9a.75.75 0 0 1 0 1.5zm6.818-8.022a.75.75 0 0 1 .364-1.456l4 1a.75.75 0 1 1-.364 1.456z");
}

.xedf9ccsf {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
