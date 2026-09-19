<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g_co-bczp"/><ellipse class="khg1uabej"/><path class="afbszib1l"/><circle class="usl73-bdq"/><circle class="h7jjbzb0z"/><circle class="a909zh9aj"/><path class="zawc5bcxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mdemu" /></template>
<style>
.a909zh9aj {
  cx: 38.059px;
  cy: 21.785px;
  r: 1.164px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.afbszib1l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.847 20.223a3.3 3.3 0 0 0-.784.103v1.828c0 .34-.271.612-.609.612H9.641a3.3 3.3 0 0 0-.102.783c.003.266.037.532.102.79h1.816a.61.61 0 0 1 .609.613v1.82q.384.098.78.102q.397-.005.781-.102v-1.823c0-.34.274-.615.612-.615h1.813q.098-.387.102-.785q0-.399-.095-.785h-1.825a.61.61 0 0 1-.61-.613v-1.833a3.3 3.3 0 0 0-.777-.095m11.147 9.05c4.631 0 7.705.93 8.772 3.709s4.042 3.998 6.978 1.383c2.936-2.614 4.81-7.335 4.755-10.163c-.056-2.829-.97-5.954-4.573-8.078S30.211 12.191 24 12.191");
}

.g_co-bczp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.006 29.273c-4.631 0-7.705.93-8.772 3.709s-4.042 3.998-6.978 1.383C5.32 31.751 3.446 27.03 3.5 24.202c.056-2.829.97-5.954 4.573-8.078S17.789 12.191 24 12.191");
}

.h7jjbzb0z {
  cx: 34.4px;
  cy: 23.185px;
  r: 1.164px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.khg1uabej {
  cx: 12.847px;
  cy: 23.549px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.814px;
  ry: 5.846px;
}

.usl73-bdq {
  cx: 31.073px;
  cy: 25.25px;
  r: 1.164px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zawc5bcxo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.02 20.413c-1.282.637-3.645 2.269-3.645 2.269c-1.436.894-2.132 2.589-1.38 4.1a3.06 3.06 0 0 0 4.103 1.372c1.293-.642 2.364-1.63 3.646-2.267s4.008-1.54 4.008-1.54c1.58-.606 2.135-2.588 1.383-4.1c-.753-1.511-2.526-1.977-4.106-1.371c0 0-2.728.9-4.01 1.537Zm-2.268-1.873l2.705-1.095");
}

</style>
