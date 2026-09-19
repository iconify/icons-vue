<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="qp-e2ubqx"/><path class="l8g6labar"/><path class="i-p9ulb_j"/><path class="yareu9vcg"/><g class="pyw7o_brn"><ellipse class="uvlkz5b5u"/><ellipse class="jla849slv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:skull" /></template>
<style>
.i-p9ulb_j {
  fill: var(--svg-color--b3b3b3, #b3b3b3);
  d: path("M50.909 49.988c0-7.555-5.553-13.679-12.404-13.679H25.511c-6.851 0-12.404 6.124-12.404 13.679c0 5.01 2.45 9.379 6.093 11.761v-7.612h4.764v9.411c.507.07 1.02.118 1.546.118h4.113v-9.529h4.767v9.529h4.114c.56 0 1.108-.056 1.648-.134v-9.396h4.762v7.544c3.59-2.397 5.995-6.73 5.995-11.692");
}

.jla849slv {
  cx: 53.865px;
  cy: 41.41px;
  rx: 8.581px;
  ry: 7.04px;
}

.l8g6labar {
  fill: var(--svg-color--405866, #405866);
  d: path("M28.2 22.843c0 4.964-4.03 8.988-8.994 8.988c-4.974 0-9-4.02-9-8.988c0-4.962 4.03-8.986 9-8.986c4.966 0 8.994 4.02 8.994 8.986m25.715 0c0 4.964-4.03 8.988-8.994 8.988c-4.974 0-9-4.02-9-8.988c0-4.962 4.03-8.986 9-8.986c4.966 0 8.994 4.02 8.994 8.986");
}

.pyw7o_brn {
  fill: var(--svg-color--b3b3b3, #b3b3b3);
}

.qp-e2ubqx {
  fill: var(--svg-color--b3b3b3, #b3b3b3);
  d: path("M64.016 26.319c0 14.541-14.332 26.325-32.005 26.325C14.327 52.645 0 40.86 0 26.319C0 11.786 14.327 0 32.01 0c17.674 0 32.006 11.786 32.006 26.319");
}

.uvlkz5b5u {
  cx: 10.152px;
  cy: 41.41px;
  rx: 8.58px;
  ry: 7.04px;
}

.yareu9vcg {
  fill: var(--svg-color--405866, #405866);
  d: path("M19.2 54.14v7.612a11.6 11.6 0 0 0 4.764 1.799V54.14zm10.424 0h4.767v9.529h-4.767zm10.526 0v9.396a11.56 11.56 0 0 0 4.762-1.852V54.14zm-.586-12.73c-.202 0-3.863-1.168-7.556-1.168c-3.297 0-6.629 1.168-7.552 1.168c-.805 0-1.102-1.518-.616-2.427c4.418-8.322 11.916-8.322 16.338 0c.48.909.183 2.427-.614 2.427");
}

</style>
