<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fzozhubqs"/><circle class="v1ngi3bkh"/><path class="c0i0hgb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rk-noe-hedu" /></template>
<style>
.c0i0hgb0f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.802 42.498v-9.314h2.096a4.074 4.074 0 0 1 4.074 4.075v1.165a4.074 4.074 0 0 1-4.074 4.074zm8.958-9.314v6.23a3.085 3.085 0 1 0 6.171 0v-6.23M27.978 13.775V5.5h-7.983v8.275m7.983 7.983h8.275v-7.983h-8.275m-7.983 7.983v8.274h7.983v-8.274m-7.983-7.983H11.72v7.983h8.275");
}

.fzozhubqs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.069 33.045v9.315m6.171-9.315v9.315m-6.171-4.676h6.17m2.996.158h3.036m1.62 4.656h-4.656v-9.314h4.656");
}

.v1ngi3bkh {
  cx: 23.247px;
  cy: 42.238px;
  r: 0.75px;
  fill: currentColor;
}

</style>
