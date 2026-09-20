<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xm9uzjeuh"/><path class="ooh-0clmn"/><path class="xg_sn7q3e"/><path class="ct_yv7biu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:uv-index" /></template>
<style>
.ct_yv7biu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.968 20.555l-2.3 6.89l-2.298-6.89m-7.338 0v4.608a2.29 2.29 0 0 0 2.298 2.282h.002a2.29 2.29 0 0 0 2.298-2.282v-4.608");
}

.ooh-0clmn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.567 24c0 9.15-7.417 16.567-16.567 16.567S7.433 33.15 7.433 24S14.85 7.433 24 7.433S40.567 14.85 40.567 24");
}

.xg_sn7q3e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.22 24c0 6.197-5.023 11.22-11.22 11.22S12.78 30.197 12.78 24S17.803 12.78 24 12.78S35.22 17.803 35.22 24");
}

.xm9uzjeuh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24c0 11.874-9.626 21.5-21.5 21.5S2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24");
}

</style>
