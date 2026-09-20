<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGd7TneboM"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path clip-rule="evenodd" class="a481t4_ci"/><path clip-rule="evenodd" class="zs2pmbc7b"/><path clip-rule="evenodd" class="r7n8j-fxl"/><path clip-rule="evenodd" class="j26bxyb6t"/><path clip-rule="evenodd" class="dtqljsa8r"/><path class="q8ipi96_k"/><path clip-rule="evenodd" class="fj1ez8bxg"/></g></mask></defs><circle mask="url(#SVGd7TneboM)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:monitor-eye-circle-filled" /></template>
<style>
.a481t4_ci {
  fill-rule: evenodd;
  d: path("M7.5 7.5A2.5 2.5 0 0 1 10 5h9.782a2.5 2.5 0 0 1 2.5 2.5v7.231a2.5 2.5 0 0 1-2.5 2.5H15.89v1.84a1 1 0 1 1-2 0v-1.846a1 1 0 0 1 .11-1.994h5.782a.5.5 0 0 0 .5-.5V7.5a.5.5 0 0 0-.5-.5H10a.5.5 0 0 0-.5.5v1.258a1 1 0 0 1-2 0z");
}

.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.dtqljsa8r {
  fill-rule: evenodd;
  d: path("M4.037 11.208a.9.9 0 0 0-.309 1.234l.735 1.225a.9.9 0 0 0 1.543-.926l-.734-1.225a.9.9 0 0 0-1.235-.308m8.761 0a.9.9 0 0 1 .309 1.234l-.735 1.225a.9.9 0 0 1-1.543-.926l.734-1.225a.9.9 0 0 1 1.235-.308");
}

.fj1ez8bxg {
  fill-rule: evenodd;
  d: path("M8.665 14.63a.25.25 0 1 0-.5 0a.25.25 0 0 0 .5 0m-.25 1.75a1.75 1.75 0 1 1 0-3.5a1.75 1.75 0 0 1 0 3.5");
}

.ft5dv1b6b {
  fill: none;
}

.ivjvz2eii {
  fill: var(--svg-color--000, #000);
}

.j26bxyb6t {
  fill-rule: evenodd;
  d: path("M10.553 10.362a.9.9 0 0 1 .706 1.06l-.245 1.224a.9.9 0 0 1-1.765-.353l.245-1.225a.9.9 0 0 1 1.059-.706m-4.271 0a.9.9 0 0 0-.706 1.06l.245 1.224a.9.9 0 0 0 1.765-.353l-.245-1.225a.9.9 0 0 0-1.059-.706");
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.q8ipi96_k {
  d: path("M8.415 13.88a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5");
}

.r7n8j-fxl {
  fill-rule: evenodd;
  d: path("M8.417 10.1a.9.9 0 0 1 .9.9v1.469a.9.9 0 0 1-1.8 0V11a.9.9 0 0 1 .9-.9");
}

.zs2pmbc7b {
  fill-rule: evenodd;
  d: path("M10.695 19.645a1 1 0 0 1 1-1h6.391a1 1 0 0 1 0 2h-6.39a1 1 0 0 1-1-1M6.138 15.36c.533.3 1.337.516 2.28.516s1.746-.217 2.28-.517c.564-.317.637-.6.637-.686s-.073-.37-.638-.687c-.533-.3-1.337-.517-2.28-.517s-1.746.217-2.28.517c-.564.318-.637.6-.637.687c0 .086.073.369.638.686m-.98 1.742c-.854-.48-1.658-1.3-1.658-2.43s.804-1.95 1.657-2.43c.885-.497 2.04-.773 3.26-.773c1.221 0 2.376.276 3.26.774c.854.48 1.658 1.3 1.658 2.43s-.804 1.95-1.657 2.43c-.885.497-2.04.773-3.26.773c-1.222 0-2.376-.276-3.26-.774");
}

</style>
