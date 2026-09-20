<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":209};
const content = `<defs><linearGradient id="SVGvYykzHSh" x1="0%" x2="100%" y1="50%" y2="50%"><stop offset="0%" class="rfmk4_bha"/><stop offset="100%" class="qbbtv9x_n"/></linearGradient><linearGradient id="SVGF9WwgdES" x1="100%" x2="0%" y1="50%" y2="50%"><stop offset="0%" class="cg8qcx4dj"/><stop offset="100%" class="uhuf3mb4d"/></linearGradient></defs><path class="h1b4n7ocv"/><path class="jwzzjabhb"/><path class="fyex88bef"/><path fill="url(#SVGvYykzHSh)" class="uyfmgejeb"/><path fill="url(#SVGvYykzHSh)" class="uvilak3if"/><path fill="url(#SVGF9WwgdES)" class="x2xsw3b2j"/><path class="bsaipeiai"/><path fill="url(#SVGF9WwgdES)" class="j9zl2mbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:webcomponents" /></template>
<style>
.bsaipeiai {
  fill: var(--svg-color--010101, #010101);
  d: path("M124.962 207.738L64.878 103.869L125.761 0H59.924L0 103.869l59.924 103.869z");
}

.cg8qcx4dj {
  stop-color: var(--svg-color--b4d44e, #b4d44e);
}

.fyex88bef {
  fill: var(--svg-color--166da5, #166da5);
  d: path("m224.676 48.898l-41.867 50.816l-25.408-42.506L196.871.16z");
}

.h1b4n7ocv {
  fill: var(--svg-color--166da5, #166da5);
  d: path("m255.997 104.029l-27.805 46.82l-38.991-47.46l38.991-46.181z");
}

.j9zl2mbdl {
  d: path("M182.809 108.024h70.631l-25.408 42.825h-70.791");
  opacity: var(--svg-opacity--0-95, 0.95);
}

.jwzzjabhb {
  fill: var(--svg-color--8fdb69, #8fdb69);
  d: path("m225.156 158.839l-42.347-50.656l-25.408 42.507l39.47 57.687z");
}

.qbbtv9x_n {
  stop-color: var(--svg-color--29abe2, #29abe2);
}

.rfmk4_bha {
  stop-color: var(--svg-color--2a3b8f, #2a3b8f);
}

.uhuf3mb4d {
  stop-color: var(--svg-color--e7f716, #e7f716);
}

.uvilak3if {
  d: path("M182.809 99.874h70.631l-25.408-42.826h-70.791");
  opacity: var(--svg-opacity--0-95, 0.95);
}

.uyfmgejeb {
  d: path("M96.997 48.898h127.679L196.552.16h-71.43z");
  opacity: var(--svg-opacity--0-95, 0.95);
}

.x2xsw3b2j {
  d: path("M225.156 158.999H96.838l28.124 48.739h71.909z");
  opacity: var(--svg-opacity--0-95, 0.95);
}

</style>
