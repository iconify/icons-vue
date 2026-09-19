<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gly2li6iw"/><path class="aezblpb-s"/><path class="us0d6db1j"/><path class="sd-bnkfeq"/><circle class="l5zgz5i_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:papago" /></template>
<style>
.aezblpb-s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.609 7.784a9.209 9.209 0 1 0 6.511 15.72l-6.511-6.369m0 0v9.066");
}

.gly2li6iw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.76 17.135c0-6.711-5.44-12.151-12.151-12.151v12.151z");
}

.l5zgz5i_t {
  cx: 22.875px;
  cy: 15.58px;
  r: 1.555px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.sd-bnkfeq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.609 4.984c-.46 0-.91.03-1.356.08l.007-.006s-7.6 1.068-11.839-.558c.182 2.294 2.224 4.04 3.723 5.023a12.1 12.1 0 0 0-2.687 7.612c0 8.709-.956 17.413-5.217 21.675c7.143 0 10.105.392 14.984-6.287");
}

.us0d6db1j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.409 38.81v4.69c8.247 0 18.711-5.082 18.711-12.429v-7.567");
}

</style>
