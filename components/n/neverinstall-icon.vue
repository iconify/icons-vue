<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":246};
const content = `<path class="qsmaz-b4e"/><path class="ma0_ykb-q"/><path class="cx49_vjrr"/><path class="iauy55b6f"/><path class="ul3pm4bye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:neverinstall-icon" /></template>
<style>
.cx49_vjrr {
  fill: var(--svg-color--ffc629, #ffc629);
  d: path("M85.661 0L0 49.821l85.661 49.231l84.677-49.231z");
}

.iauy55b6f {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("m0 49.821l85.66 49.23l84.678-49.23L85.66 0zm15.983-.041l69.655 40.032l68.854-40.032L85.637 9.268z");
}

.ma0_ykb-q {
  fill: var(--svg-color--2962ff, #2962ff);
  d: path("m85.662 99.077l84.676-49.23L256 99.077v97.083l-85.662 49.231v-97.083z");
}

.qsmaz-b4e {
  fill: var(--svg-color--5b29ff, #5b29ff);
  d: path("M85.661 99.099L0 148.133V49.868z");
}

.ul3pm4bye {
  fill: var(--svg-color--ffbc00, #ffbc00);
  d: path("M85.654 89.856V9.34L16 49.849z");
}

</style>
