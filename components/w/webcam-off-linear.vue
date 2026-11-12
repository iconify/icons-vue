<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cu1491zmm"/><path class="rsrhfac5n"/><path class="v_cyp7bey"/><path class="n3am1gblp"/><path class="kva043bzk"/><path class="t26d7g3rg"/><path class="bdz-ljbiy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:webcam-off-linear" /></template>
<style>
.bdz-ljbiy {
  d: path("M9.6543 17.6507C10.3962 17.8779 11.1839 18.0002 12.0002 18.0002C16.4184 18.0002 20.0002 14.4184 20.0002 10.0002C20.0002 9.18388 19.8779 8.39616 19.6507 7.6543");
}

.cu1491zmm {
  d: path("M14.8715 9.12853C14.4981 7.89669 13.3538 7 12 7C10.3431 7 9 8.34315 9 10C9 11.3538 9.8967 12.4981 11.1285 12.8715");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kva043bzk {
  d: path("M16 22H8");
}

.n3am1gblp {
  d: path("M18.5246 5.47544C17.0618 3.3948 14.6512 2.02218 11.9354 2.00027C7.51731 1.96461 3.96461 5.51731 4.00027 9.93545C4.02218 12.6512 5.3948 15.0618 7.47545 16.5246");
}

.rsrhfac5n {
  d: path("M22 2L2 22");
}

.t26d7g3rg {
  d: path("M12 18.0031V22");
}

.v_cyp7bey {
  stroke-linejoin: round;
  d: path("M12 4.50098H12.0001");
}

</style>
