<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><g class="n1mjunbsu"><path class="tr0nibcbj"/><circle class="x7eknnb-v"/><path class="kr1-m7bif"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:wheelchair-symbol" /></template>
<style>
.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

.kr1-m7bif {
  d: path("M29.4 48.9c-4.5 0-8.2-3.7-8.2-8.2c0-3 1.7-5.7 4.1-7.1V29c-4.8 1.7-8.2 6.3-8.2 11.6C17 47.5 22.6 53 29.4 53c3.9 0 7.4-1.8 9.6-4.6l-2.5-3.7c-1.4 2.5-4.1 4.2-7.1 4.2");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.tr0nibcbj {
  d: path("m48.7 43l-2.5 2.7l-6-9.2H33v-4.1h8v-4.2h-8V20h-4v20.6h9.1L45.5 52l5.5-5.6z");
}

.x7eknnb-v {
  cx: 31px;
  cy: 13px;
  r: 4px;
}

</style>
