<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="plw-owhdh"/><path class="yjc9h6oua"/><path class="u76bw-bhz"/><path class="q1_6fmhmb"/><path class="eg-6zob1i"/><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="lip701r7h"/><path class="kikp0-sku"/><path class="jsj5j3bdw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ndcg-duotone-bold" /></template>
<style>
.eg-6zob1i {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 10.5V13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ffw_pwyfz {
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
}

.jsj5j3bdw {
  d: path("M13 10.5V13");
}

.kfdmhd64i {
  d: path("m15 15 6 6");
}

.kikp0-sku {
  d: path("M10 9v4");
}

.lip701r7h {
  d: path("M7 7v6");
}

.plw-owhdh {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q1_6fmhmb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 9v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u76bw-bhz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 7v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yjc9h6oua {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 15 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
