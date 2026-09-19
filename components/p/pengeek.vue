<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="j8pkdxe3w"/><circle class="y2bbkrb3u"/><path class="olhbg2l8a"/></g><g class="y9tr6bcfx"><circle class="lcr5ro0lg"/><circle class="laewr4jqj"/><path class="le6rm_olc"/></g><g class="y9tr6bcfx"><path class="a7t4vxbpb"/><circle class="kxf1erxci"/><path class="fhhp1pg4b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pengeek" /></template>
<style>
.a7t4vxbpb {
  d: path("M12.672 20.857C12.672 14.6 17.743 9.529 24 9.529h0c6.257 0 11.329 5.071 11.329 11.328h0");
}

.fhhp1pg4b {
  d: path("M24 9.529V7.407m8.003 5.433l1.5-1.501l-6.432 6.432M15.997 12.84l-1.5-1.501l6.432 6.432m6.034-7.848l.55-2.05m2.187 3.194l1.06-1.838m3.091 6.034l1.838-1.06m-.727 3.796l2.05-.55M21.037 9.923l-.55-2.05M18.3 11.067l-1.06-1.838m-3.091 6.034l-1.838-1.06m.727 3.796l-2.05-.55");
}

.j8pkdxe3w {
  cx: 34.424px;
  cy: 31.517px;
  r: 6.987px;
}

.kxf1erxci {
  cx: 24px;
  cy: 20.857px;
  r: 4.354px;
}

.laewr4jqj {
  cx: 13.576px;
  cy: 31.517px;
  r: 3.608px;
}

.lcr5ro0lg {
  cx: 13.576px;
  cy: 31.517px;
  r: 6.987px;
}

.le6rm_olc {
  d: path("M13.576 24.53v-2.089m0 18.152v-2.089m6.987-6.987h2.09m-18.153 0h2.09m3.493-6.05l-1.045-1.81m9.076 15.72l-1.044-1.809m-9.545-9.544l-1.81-1.045m15.721 9.076l-1.809-1.044m-2.557-9.544l1.044-1.81m-9.076 15.72l1.045-1.809m9.544-9.544l1.81-1.045M5.716 36.055l1.81-1.044");
}

.olhbg2l8a {
  d: path("M34.424 24.53v-2.089m0 18.152v-2.089m6.986-6.987h2.09m-18.152 0h2.089m3.493-6.05l-1.044-1.81m9.076 15.72l-1.044-1.809m-9.545-9.544l-1.81-1.045m15.721 9.076l-1.81-1.044m-2.557-9.544l1.045-1.81m-9.076 15.72l1.044-1.809m9.545-9.544l1.81-1.045m-15.721 9.076l1.809-1.044");
}

.y2bbkrb3u {
  cx: 34.424px;
  cy: 31.517px;
  r: 3.608px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
