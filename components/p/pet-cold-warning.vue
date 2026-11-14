<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qklufabjo"/><path class="h9nebm09t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pet-cold-warning" /></template>
<style>
.h9nebm09t {
  d: path("M7.5 19.5v-4a2.5 2.5 0 0 1 5 0v4m2.75-1h6.5m-4.875-2.815l3.25 5.63m0-5.63l-3.25 5.63");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qklufabjo {
  d: path("M12.64 19.5H4.75q-.086 0-.172-.008t-.169-.026q-.085-.016-.167-.041t-.162-.058q-.079-.033-.155-.074t-.147-.088q-.072-.048-.138-.102q-.067-.055-.127-.116q-.061-.06-.116-.127q-.054-.066-.102-.138q-.048-.071-.088-.147q-.041-.076-.074-.155q-.033-.08-.058-.162t-.041-.167t-.026-.169Q3 17.836 3 17.75v-6.951q0-.188.04-.372t.118-.355t.191-.321q.113-.151.255-.274l5.75-4.984q.059-.051.122-.097q.064-.046.131-.085t.138-.074q.07-.034.143-.061q.074-.027.149-.048t.152-.035t.155-.02q.078-.007.156-.007t.156.007t.155.02t.152.035t.149.048q.073.027.143.061q.071.034.138.074t.131.085q.063.046.122.097l5.75 4.984q.142.123.255.274q.113.15.191.321t.118.355t.04.372v2.336");
}

</style>
