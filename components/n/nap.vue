<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="mz4vo0btk"><path class="e5xzsq5wf"/><path class="lhny41bxk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nap" /></template>
<style>
.e5xzsq5wf {
  d: path("m13.997 18.036l-.148.047a6.356 6.356 0 1 1 .147-.047m-3.41-9.741H8.295v.524h.244l.285.31v5.519s0 .529-.529.529v.53h1.588v-.53s-.53-.027-.53-.53V9.704l5.539 6.003h.285V9.353s0-.53.53-.53v-.528h-1.588v.529s.529 0 .529.53v3.404z");
}

.lhny41bxk {
  d: path("M18.364 5.636A9 9 0 1 0 5.636 18.364A9 9 0 0 0 18.364 5.636m-3.73.007a6.885 6.885 0 1 0-5.274 12.72a6.885 6.885 0 0 0 5.275-12.72");
}

.mz4vo0btk {
  fill: var(--svg-color--03a7e4, #03a7e4);
  fill-rule: evenodd;
}

</style>
