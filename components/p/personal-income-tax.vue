<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="jxlk20bew"/><path class="lf3zrtbqq"/><path class="dxzoh8fuw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:personal-income-tax" /></template>
<style>
.dxzoh8fuw {
  d: path("M31.377 27.368h-.611c-.78 0-1.407-.626-1.407-1.405v-3.631q0-.05.003-.098m-3.647 2.113c-.27 1.331-.658 2.559-1.567 2.928");
}

.jxlk20bew {
  d: path("M7.163 9.749C12.826 9.109 18.69 7.196 24 4.5c5.31 2.696 11.174 4.61 16.837 5.249C41.457 23.4 36.886 35.524 24 43.5C11.114 35.524 6.544 23.401 7.163 9.749m10.076 5.15h4.585m-4.585 2.671h4.585m-2.293-2.672v12.668m2.293-7.711v7.577");
}

.lf3zrtbqq {
  d: path("M17.537 19.855v6.256c0 .502-.063 1.124-.524 1.321m7.075-12.533h1.576m3.549 0h1.576m-6.537 7.336v-4.93h6.633v4.227c0 .39-.314.703-.704.703z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
