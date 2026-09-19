<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="mwur4d4wl"/><path class="lj9ocrb5e"/><path class="grare0p2o"/><path class="gsn5fibpa"/><path class="mycgv_baf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sagawa-express" /></template>
<style>
.grare0p2o {
  d: path("M15.715 17.497h7.963l-1.889-3.158M7.897 17.497h.553");
}

.gsn5fibpa {
  d: path("M8.45 14.123h9.169v6.715H8.45zm16.329-9.597c11.58 3.794 6.635 8.394 1.329 11.607");
}

.lj9ocrb5e {
  d: path("M25.95 19.768L40.102 43.5H37.83L23.615 26.66l-2.886 2.475l7.22 2.66M16.334 10.102h3.612m7.18 11.602h-7.564m-5.984-10.002l1.449 2.421m8.369-.713l-1.39-2.409c-.523-.906-1.653-1.227-2.534-.718s-1.168 1.648-.645 2.555l1.39 2.409zm-11.042-1.914c-.09.439-.022.916.223 1.342l.742 1.284");
}

.mwur4d4wl {
  d: path("M16.823 8.39a3.319 3.319 0 1 1-3.318-3.32a3.32 3.32 0 0 1 3.318 3.32m1.58 11.376l1.16 1.938l-6.805 9.399l18.013 4.035");
}

.mycgv_baf {
  d: path("M29.924 4.5c11.608 2.262 8.182 9.958-2.746 13.487");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
