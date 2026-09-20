<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="tdezt_kit"/><path class="tyvw42b6f"/><path class="y-8u9wb8b"/><path class="nu0ti3ggl"/><path class="h2sq3fbpa"/><path class="sjev68umd"/><path class="oe-98mb0w"/><path class="vdq8lyksd"/><path class="vhnbtvbtn"/><path class="xyj-l9cjp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:winsorize-duotone-bold" /></template>
<style>
.h2sq3fbpa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nu0ti3ggl {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 8h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oe-98mb0w {
  d: path("M12 6v12");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sjev68umd {
  d: path("M6 11v7");
}

.tdezt_kit {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 11v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tyvw42b6f {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vdq8lyksd {
  d: path("M18 12v6");
}

.vhnbtvbtn {
  d: path("M3 8h18");
}

.xyj-l9cjp {
  d: path("M3 18h18");
}

.y-8u9wb8b {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 12v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
