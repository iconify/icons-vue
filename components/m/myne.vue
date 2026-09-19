<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="rkw1ugq5i"/><path class="vigm8ubnh"/></g><g class="y9tr6bcfx"><path class="pqxrg9bvs"/><path class="d7j_knlzw"/></g><path class="lgmdp_bcq"/><path class="teh6g0bfx"/><path class="fldv6bb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:myne" /></template>
<style>
.d7j_knlzw {
  d: path("M26.162 32.117c1.752-1.752 1.752-8.159 0-9.91");
}

.fldv6bb2c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.693 9.03s-1.192-5.02 4.437-4.49c0 0 2.394 4.721-4.436 4.49");
}

.lgmdp_bcq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.068 10.818s.906-.675 1.676-.675c3.32 0 4.854 1.843 5.264 4.727c.539 3.799-.998 5.863-3.25 6.663c-2.125.755-6.288.53-8.02-.32c-1.896-.93-3.17-3.303-2.404-6.257c.883-3.412 2.64-5.634 6.734-4.138");
}

.pqxrg9bvs {
  d: path("M7.22 25.288h16.327c.663.662.663 3.084 0 3.747H7.22c-.545.545-.545 2.537 0 3.082h32.655c1.752-1.752 1.752-8.159 0-9.91H7.22c-.545.544-.545 2.536 0 3.08m1.389 3.748v-3.747");
}

.rkw1ugq5i {
  d: path("M40.72 39.96h-16.2c-.76-.76-.76-3.543 0-4.304h16.2c.625-.625.625-2.914 0-3.54H8.32c-2.012 2.013-2.012 9.372 0 11.384h32.4c.625-.626.625-2.914 0-3.54m-1.597-4.304v4.304");
}

.teh6g0bfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.108 6.544s1.231 3.215 2.96 4.274");
}

.vigm8ubnh {
  d: path("M21.517 32.117c-2.012 2.012-2.012 9.37 0 11.383");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
