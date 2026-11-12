<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lfpfczh4t"/><path class="zl3fw2elx"/><path class="lywtx37wy"/><path class="y-uxy98jv"/><path class="ljiiezm4y"/><path class="gs9bj9biz"/><path class="t-j_eedxl"/><path class="gof8c6bpn"/><path class="m0suawb_f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:table-columns-split-broken" /></template>
<style>
.gof8c6bpn {
  d: path("M22.0322 8.6665L16.0043 8.6665");
}

.gs9bj9biz {
  d: path("M11 14C11 17.7712 11 19.6569 9.82843 20.8284C8.65685 22 6.77124 22 3 22L2 22");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lfpfczh4t {
  d: path("M2 15.333L11 15.333");
}

.ljiiezm4y {
  d: path("M11 10C11 6.22876 11 4.34315 9.82843 3.17157C8.65685 2 6.77124 2 3 2L2 2");
}

.lywtx37wy {
  d: path("M5 2.00879L5 21.9914");
}

.m0suawb_f {
  d: path("M21.9918 2.00879C19.5201 2.0451 18.1175 2.23 17.176 3.17149C16.0044 4.34306 16.0044 6.22868 16.0044 9.99992L16.0044 13.9999C16.0044 17.7712 16.0044 19.6568 17.176 20.8283C18.1183 21.7707 19.5227 21.9551 21.9987 21.9911");
}

.t-j_eedxl {
  d: path("M21.9985 15.333L16.0043 15.333");
}

.y-uxy98jv {
  d: path("M13.5 2.00879V3.67267M13.5 20.3502V22.014M13.5 7.00269V10.3488M13.5 13.66V17.0062");
}

.zl3fw2elx {
  d: path("M2 8.6665L11 8.6665");
}

</style>
