<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xjlw5hbpn"/><path class="s7z29qb4q"/><path class="y4mdv3b1r"/><path class="r856z_4kt"/><path class="ai3rdhbcu"/><path class="buz9ww_ue"/><path class="hcn-wubvk"/><path class="toy0nxbdm"/><path class="ler50rfbf"/><path class="caiwqabfd"/><path class="qw9zcf0wd"/><path class="beunabbsv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:overtake-duotone-regular" /></template>
<style>
.ai3rdhbcu {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 4v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.beunabbsv {
  d: path("M12.5 6.5 15 4l2.5 2.5");
}

.buz9ww_ue {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12.5 6.5 15 4l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.caiwqabfd {
  d: path("M6.5 10.5 9 8l2.5 2.5");
}

.hcn-wubvk {
  d: path("M3 2v20");
}

.ler50rfbf {
  d: path("M9 8v12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qw9zcf0wd {
  d: path("M15 4v12");
}

.r856z_4kt {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6.5 10.5 9 8l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s7z29qb4q {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M21 2v20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.toy0nxbdm {
  d: path("M21 2v20");
}

.xjlw5hbpn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 2v20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y4mdv3b1r {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
