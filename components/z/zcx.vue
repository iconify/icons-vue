<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="puu3xp2jj"/><path class="k8cwu6c2k"/><path class="lbldjkz4h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:zcx" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k8cwu6c2k {
  fill: var(--svg-color--00afa4, #00afa4);
  d: path("M20.91 8.614h-9.112l3.116-2.807h-2.257L8.62 9.457l3.83 4.21H8.765A6.748 6.748 0 0 1 14.246 3a6.745 6.745 0 0 1 6.659 5.614zm.073 1.685h-9.365l3.762 4.21l-2.077 1.898a6.75 6.75 0 0 0 7.68-6.108m-9.382 5.637l.663-.584h-1.746q.515.34 1.083.584");
}

.lbldjkz4h {
  fill: var(--svg-color--01d5a3, #01d5a3);
  d: path("M13.482 8.615a7 7 0 0 0-1.05-.573l-.634.573zm-1.033 5.053L8.632 9.457l2.094-1.898a6.8 6.8 0 0 0-2.931.225a6.74 6.74 0 0 0 .977 5.884zm2.78-3.369h-3.61l3.75 4.21l-2.072 1.899a6.8 6.8 0 0 0 2.909-.225a6.74 6.74 0 0 0-.977-5.884m-4.711 5.053q.512.338 1.084.584l.657-.584z");
}

.puu3xp2jj {
  fill: var(--svg-color--05f1a4, #05f1a4);
  d: path("m10.72 7.56l-2.1 1.897l3.829 4.211H3.017A6.75 6.75 0 0 1 10.72 7.56m1.712.482l-.634.573h1.684a6.5 6.5 0 0 0-1.05-.573M15.24 10.3h-3.621l3.762 4.21l-3.987 3.65H9.08l3.184-2.808H3.09A6.755 6.755 0 1 0 15.234 10.3z");
}

</style>
