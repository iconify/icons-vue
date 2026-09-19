<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="sbxixybog"/><g class="n1mjunbsu"><ellipse class="nikv3vlvp"/><path class="ofcj0ejwq"/><ellipse class="z9wwzvbxf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:speech-balloon" /></template>
<style>
.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.nikv3vlvp {
  cx: 14.885px;
  cy: 27.1px;
  rx: 4.572px;
  ry: 3.782px;
}

.ofcj0ejwq {
  d: path("M31.908 23.316c-2.527 0-4.574 1.692-4.574 3.781c0 2.088 2.047 3.782 4.574 3.782c2.523 0 4.57-1.694 4.57-3.782s-2.046-3.781-4.57-3.781");
}

.sbxixybog {
  fill: var(--svg-color--67b0dd, #67b0dd);
  d: path("M31.908 5C14.286 5 0 14.556 0 26.342c0 6.61 4.495 12.518 11.547 16.432c-.87 2.877-3.372 6.49-9.717 9.89c0 0-1.83 1.235 0 2.746c0 0 12.267.725 20.98-8.609c2.883.573 5.933.886 9.1.886c17.619 0 31.904-9.556 31.904-21.342C63.814 14.556 49.529 5 31.91 5");
}

.z9wwzvbxf {
  cx: 48.643px;
  cy: 27.1px;
  rx: 4.571px;
  ry: 3.782px;
}

</style>
