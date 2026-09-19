<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kouz2_bms"/><path class="zxyg6zbyz"/><path class="o2r79bcca"/><path class="hac7hlb7r"/><path class="r5_m_jw4n"/><path class="rpjkl4qgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:openai-chatgpt" /></template>
<style>
.hac7hlb7r {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M30.5 21.2v14.14L19.31 41.8c-6.2 3.58-17.3-5.25-12.64-13.33");
}

.kouz2_bms {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M18.38 27.94v-14.4l11.19-6.46c6.2-3.58 17.3 5.25 12.64 13.33");
}

.o2r79bcca {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("m24.44 17.44l12.47 7.2v12.93c0 7.16-13.2 12.36-17.86 4.28");
}

.r5_m_jw4n {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("m30.5 27.94l-12.47 7.2l-11.19-6.46c-6.21-3.59-4.11-17.61 5.22-17.61");
}

.rpjkl4qgl {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("m24.44 31.44l-12.47-7.2V11.31c0-7.16 13.2-12.36 17.86-4.28");
}

.zxyg6zbyz {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("m18.38 20.94l12.47-7.2l11.19 6.46c6.2 3.58 4.1 17.61-5.23 17.61");
}

</style>
