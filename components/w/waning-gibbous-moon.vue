<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="kqma3lb9x"/><path class="v0ku3kiqh"/><g class="eyuj09bzi"><circle class="t3ijnw0sk"/><path class="j4a__9wph"/><circle class="orq25tb1j"/><circle class="lnsdnwbmj"/><path class="imsq7i54p"/><circle class="rikus-b_m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:waning-gibbous-moon" /></template>
<style>
.eyuj09bzi {
  fill: var(--svg-color--e0cf35, #e0cf35);
}

.imsq7i54p {
  d: path("M21.17 20a3.406 3.406 0 1 1-6.811 0a3.406 3.406 0 0 1 6.811 0");
}

.j4a__9wph {
  d: path("M41.95 24.793a3.89 3.89 0 0 1-7.777 0a3.89 3.89 0 0 1 7.777 0");
}

.kqma3lb9x {
  cx: 32.12px;
  cy: 32.372px;
  r: 31.63px;
  fill: var(--svg-color--f5eb35, #f5eb35);
}

.lnsdnwbmj {
  cx: 6.633px;
  cy: 19.266px;
  r: 2.177px;
}

.orq25tb1j {
  cx: 6.289px;
  cy: 36.753px;
  r: 3.816px;
}

.rikus-b_m {
  cx: 42.934px;
  cy: 11.484px;
  r: 4.797px;
}

.t3ijnw0sk {
  cx: 29.46px;
  cy: 53.11px;
  r: 9.155px;
}

.v0ku3kiqh {
  fill: var(--svg-color--405866, #405866);
  d: path("M45.761 3.868c10.635 5.099 17.991 15.928 17.991 28.504c0 14.391-9.618 26.515-22.771 30.347c10.882-10.463 18.963-38.862 4.78-58.851");
}

</style>
