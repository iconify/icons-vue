<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sx-u-vhde"/><g class="y9tr6bcfx"><path class="b-mu_fu0s"/><path class="xdfvy2b-l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vietcombank" /></template>
<style>
.b-mu_fu0s {
  d: path("M20.584 4.987S3.049 7.143 4.861 16.31c1.96 9.918 11.197 20.114 15.251 23.112c3.528 2.608 8.073 5.624 12.94-.664c5.18-6.693 14.164-25.278 8.667-30.658");
}

.sx-u-vhde {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.696 6.073c5.44-2.773 23.353-1.376 25.543 2.703c1.294 5.695-3.128 12.285-4.688 14.626c-4.301 6.457-6.3 9.817-10.545 5.284c-7.27-7.762-15.444-20.835-10.31-22.614");
}

.xdfvy2b-l {
  d: path("M18.664 17.223c3.41-.727 21.526-2.013 20.515 3.696");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
