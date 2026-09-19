<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="jlmqckkgr"/><circle class="xspmxxb4b"/><circle class="qcqb3h20a"/><circle class="phypkibaf"/><path class="v_5ortbvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-pets" /></template>
<style>
.jlmqckkgr {
  cx: 4.5px;
  cy: 9.5px;
  r: 2.5px;
  fill: currentColor;
}

.phypkibaf {
  cx: 19.5px;
  cy: 9.5px;
  r: 2.5px;
  fill: currentColor;
}

.qcqb3h20a {
  cx: 15px;
  cy: 5.5px;
  r: 2.5px;
  fill: currentColor;
}

.v_5ortbvz {
  fill: currentColor;
  d: path("M17.34 14.86c-.87-1.02-1.6-1.89-2.48-2.91c-.46-.54-1.05-1.08-1.75-1.32q-.165-.06-.33-.09c-.25-.04-.52-.04-.78-.04s-.53 0-.79.05q-.165.03-.33.09c-.7.24-1.28.78-1.75 1.32c-.87 1.02-1.6 1.89-2.48 2.91c-1.31 1.31-2.92 2.76-2.62 4.79c.29 1.02 1.02 2.03 2.33 2.32c.73.15 3.06-.44 5.54-.44h.18c2.48 0 4.81.58 5.54.44c1.31-.29 2.04-1.31 2.33-2.32c.31-2.04-1.3-3.49-2.61-4.8");
}

.xspmxxb4b {
  cx: 9px;
  cy: 5.5px;
  r: 2.5px;
  fill: currentColor;
}

</style>
