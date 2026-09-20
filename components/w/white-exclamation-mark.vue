<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="iobffpbpw"/><g class="n1mjunbsu"><path class="q_z6bdc_d"/><circle class="uvjwupbyn"/></g><circle class="jxe5di27t"/><circle class="fkjrlfi2e"/><path class="z7a99nnwx"/><path class="w_hcjybkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:white-exclamation-mark" /></template>
<style>
.fkjrlfi2e {
  cx: 62.4px;
  cy: 112px;
  r: 10.3px;
  fill: var(--svg-color--e0e0e0, #e0e0e0);
}

.iobffpbpw {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  d: path("m69.8 88.1l1.8-80c.1-2.2-1.8-4.1-4-4.1H55.9c-2.3 0-4.1 1.9-4 4.1l1.8 80c.1 2.2 1.8 3.9 4 3.9h8c2.2 0 4-1.7 4.1-3.9");
}

.jxe5di27t {
  cx: 64.1px;
  cy: 112px;
  r: 12px;
  fill: var(--svg-color--bdbdbd, #bdbdbd);
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.q_z6bdc_d {
  d: path("M64 50c.3-1.9-.5-26.2-.5-26.2s.1-3.5-2.8-3.8c-2.8-.3-3.8 2.3-3.8 4.1s.4 21.5.6 23.3c.1 1.8 1.9 3.7 3.6 4.2s2.7-.2 2.9-1.6");
}

.uvjwupbyn {
  cx: 59.6px;
  cy: 13.4px;
  r: 3.3px;
}

.w_hcjybkv {
  fill: var(--svg-color--bdbdbd, #bdbdbd);
  d: path("M71.9 4h-4.3c2.3 0 4.1 1.9 4 4.1l-1.8 80c-.1 2.2-1.8 3.9-4 3.9H70c2.2 0 4-1.7 4-3.9l1.8-80C76 5.9 74.1 4 71.9 4");
}

.z7a99nnwx {
  fill: var(--svg-color--fff, #fff);
  d: path("M56.5 108.4c1.2-1.8 3.8-3.3 6.5-3.7c.7-.1 1.3-.1 1.9.1c.4.2.8.6.5 1c-.2.4-.7.5-1.1.6c-2.5.7-4.8 2.4-6.2 4.4c-.5.8-1.4 2.9-2.4 2.4c-1-.7-.7-2.6.8-4.8");
}

</style>
