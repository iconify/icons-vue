<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="v_cyp7bey"/><path class="kva043bzk"/><path class="t26d7g3rg"/><path class="cu1491zmm"/><path class="o5pqkb2dm"/><path class="bdz-ljbiy"/><path class="iy-m30bpe"/><path class="rsrhfac5n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:webcam-off-broken" /></template>
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

.iy-m30bpe {
  d: path("M9 2.58152C9.92643 2.20651 10.9391 2 12 2C14.7199 2 17.1229 3.3574 18.5683 5.43173");
}

.kva043bzk {
  d: path("M16 22H8");
}

.o5pqkb2dm {
  d: path("M7.43173 16.5683C5.3574 15.1229 4 12.7199 4 10C4 8.9391 4.20651 7.92643 4.58152 7");
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
