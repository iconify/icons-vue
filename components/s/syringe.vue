<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="c0izpxb_s"/><path class="a_nyv__jy"/><path class="s6ol8289i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:syringe" /></template>
<style>
.a_nyv__jy {
  d: path("M11.02 11.607a.5.5 0 1 1-.706.707l-1.415-1.415a.5.5 0 1 1 .708-.707zM5.718 16.91a1 1 0 1 1-1.415 1.414l-2.828-2.828a1 1 0 1 1 1.414-1.415zm3.667-.24a1 1 0 1 1-1.414 1.415l-5.964-5.964a1 1 0 1 1 1.414-1.414zm3.757-7.185a.5.5 0 1 1-.707.707l-1.414-1.414a.5.5 0 1 1 .707-.707z");
}

.c0izpxb_s {
  fill-rule: evenodd;
  d: path("M4.354 10.718a2.5 2.5 0 0 0 0 3.535l1.414 1.414a2.5 2.5 0 0 0 3.535 0l6.971-6.97a2.5 2.5 0 0 0 .732-1.825l-.032-1.407a2.5 2.5 0 0 0-2.473-2.444l-1.374-.014a2.5 2.5 0 0 0-1.795.732zM14.86 7.281l-6.97 6.971a.5.5 0 0 1-.708 0l-1.414-1.414a.5.5 0 0 1 0-.707l6.978-6.979a.5.5 0 0 1 .36-.146l1.374.014a.5.5 0 0 1 .495.489l.032 1.407a.5.5 0 0 1-.147.365");
}

.cuyn6tgcc {
  fill: currentColor;
}

.s6ol8289i {
  d: path("M5 16.414L3.586 15L5 13.586L6.414 15zM17.97.97a.75.75 0 0 1 1.061 1.061l-3 3a.75.75 0 0 1-1.06-1.06z");
}

</style>
