<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wumc_cb4a"/><path class="zlliqjbug"/><path class="hg2j5gbrv"/><path class="l-1iffteo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wingstop" /></template>
<style>
.hg2j5gbrv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 22.104c4.98 0 11.864 1.659 14.373 4.38l-2.36 3.318c-3.956-2.68-7.438-3.807-12.013-3.807s-8.057 1.128-12.012 3.807l-2.361-3.317c2.51-2.722 9.394-4.381 14.373-4.381");
}

.l-1iffteo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.383 29.387l-1.03.756s-3.55-1.255-5.72-.851l-.808 1.318l-1.531-.276l-.85 1.148l-1.444-.83m18.882-9.427H31.965m8.45 1.758h-9.484M24 17.368l1.408-.85l.794.962l1.673-.31l.694 1.531l2.362.589");
}

.wumc_cb4a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M3 19.29h14.127v.212c.085.553.581 1.449 1.772 2.028m-.239 1.104c.587-2.407 2.75-4.187 5.34-4.187s4.753 1.78 5.34 4.187m-10.204 3.873c.91 1.75 2.75 2.943 4.864 2.943s3.954-1.193 4.865-2.943");
}

.zlliqjbug {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.617 29.387l1.03.756s3.55-1.255 5.72-.851l.808 1.318l1.531-.276l.85 1.148l1.444-.83v-1.201M5.118 21.225h10.917m-8.45 1.758h9.484M24 18.443v-1.075l-1.408-.85l-.794.962l-1.673-.31l-.694 1.531l-2.362.589m27.931 0H30.873v.212c-.085.553-.581 1.449-1.772 2.028");
}

</style>
