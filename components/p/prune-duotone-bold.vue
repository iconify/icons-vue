<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mmx2_7bmn"/><path class="bfcre-2ir"/><path class="gg4r_qbnd"/><path class="sxcmd6bwx"/><path class="ynmtalbej"/><path class="mpjdm200q"/><path class="ngnirel9c"/><path class="hcq4p1b2v"/><path class="b1a3u6bfq"/><path class="ax4bccbjb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:prune-duotone-bold" /></template>
<style>
.ax4bccbjb {
  d: path("m20 7 -4 4");
}

.b1a3u6bfq {
  d: path("m16 7 4 4");
}

.bfcre-2ir {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 9h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gg4r_qbnd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 15h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hcq4p1b2v {
  d: path("M6 15h8");
}

.mmx2_7bmn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mpjdm200q {
  d: path("M6 4v16");
}

.ngnirel9c {
  d: path("M6 9h8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sxcmd6bwx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m16 7 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ynmtalbej {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m20 7 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
