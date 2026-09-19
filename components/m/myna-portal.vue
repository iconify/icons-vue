<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a53n_zbbu"/><ellipse class="x52ggpnbp"/><path class="v8vp12btd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:myna-portal" /></template>
<style>
.a53n_zbbu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.433 34.505c-.078.078-.79.075-.866 0m-7.296-11.532s-2.382-9.84-2.121-14.926c.092-1.8.73-3.433 2.807-3.547h0c2.063.083 2.686 1.462 2.933 3.245c.586 4.228.375 11.5.342 14.053m10.791.874s2.726-9.278 2.647-14.369c-.028-1.802-.607-3.457-2.677-3.645h0c-3.487-.334-8.107 1.75-7.771 4.416c.123.972 1.362 2.138 4.32 1.923c-.4 4.773-.392 8.567-.442 10.67");
}

.v8vp12btd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.751 26.857h1.972v5.26m11.927-5.26h1.971v5.26m-4.423 5.048c0 1.127-.61 2.169-1.599 2.732a3.24 3.24 0 0 1-3.198 0a3.15 3.15 0 0 1-1.6-2.733");
}

.x52ggpnbp {
  cx: 24px;
  cy: 32.468px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 14.843px;
  ry: 11.032px;
}

</style>
