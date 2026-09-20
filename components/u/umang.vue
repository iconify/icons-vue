<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yfrhy7bbg"/><path class="ccr7n9haq"/><path class="cpauu2b5d"/><path class="y1mp_ebkx"/><circle class="s4nyybt8m"/><path class="d_ju8c4-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:umang" /></template>
<style>
.ccr7n9haq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.206 31.881v-6.006a1.892 1.892 0 1 1 3.785 0v6.224");
}

.cpauu2b5d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.99 32.099v-4.46a1.892 1.892 0 0 1 3.785 0v4.622");
}

.d_ju8c4-c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.989 8.55h6.624");
}

.s4nyybt8m {
  cx: 21.313px;
  cy: 15.88px;
  r: 2.315px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.y1mp_ebkx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.775 32.26v-1.946a1.892 1.892 0 0 1 3.785 0v8.303c0 3.294-4.61 4.883-9.781 4.883c-7.071 0-11.339-3.208-11.339-10.124c0-.832.358-1.716 1.495-1.716c2.12 0 .796 5.61 3.132 5.61c1.665 0 1.354-2.52 1.354-4.422V21.714a1.892 1.892 0 0 1 3.785 0v10.168");
}

.yfrhy7bbg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.44 30.23V8.923A4.436 4.436 0 0 1 17.863 4.5h12.274a4.436 4.436 0 0 1 4.423 4.423v16.323");
}

</style>
