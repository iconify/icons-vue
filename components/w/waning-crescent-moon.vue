<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="zv1k9yb7t"/><path class="em48ozbmz"/><g class="ed4r-5bxj"><circle class="wu97xs7ga"/><path class="d1napvwio"/></g><g class="eyuj09bzi"><circle class="k69vn3bsy"/><circle class="ingsx9b9g"/></g><g class="ed4r-5bxj"><circle class="bm0ikf3ob"/><path class="rs-a88bhv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:waning-crescent-moon" /></template>
<style>
.bm0ikf3ob {
  cx: 17.815px;
  cy: 19.604px;
  r: 3.413px;
}

.d1napvwio {
  d: path("M42.04 24.407a3.895 3.895 0 0 1-7.791 0a3.897 3.897 0 0 1 7.791 0");
}

.ed4r-5bxj {
  fill: var(--svg-color--4f6977, #4f6977);
}

.em48ozbmz {
  fill: var(--svg-color--f5eb35, #f5eb35);
  d: path("M18.438 3.442C7.787 8.55.415 19.399.415 32c0 14.418 9.636 26.564 22.813 30.404c-10.903-10.483-18.997-38.935-4.79-58.962");
}

.eyuj09bzi {
  fill: var(--svg-color--e0cf35, #e0cf35);
}

.ingsx9b9g {
  cx: 6.659px;
  cy: 18.871px;
  r: 2.182px;
}

.k69vn3bsy {
  cx: 6.316px;
  cy: 36.39px;
  r: 3.823px;
}

.rs-a88bhv {
  d: path("M47.835 11.07a4.804 4.804 0 0 1-4.808 4.803a4.807 4.807 0 0 1-4.807-4.803a4.808 4.808 0 0 1 9.615 0");
}

.wu97xs7ga {
  cx: 29.529px;
  cy: 52.777px;
  r: 9.172px;
}

.zv1k9yb7t {
  cx: 32.2px;
  cy: 32px;
  r: 31.688px;
  fill: var(--svg-color--405866, #405866);
}

</style>
