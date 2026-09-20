<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="um_bubczs"/><path class="rpr8skgtq"/><path class="ip7qw0c-r"/><path class="f0wh-k8gw"/><path class="pxx-spbdi"/><path class="pi0o-3bfc"/><path class="ifhv18rgk"/><path class="t_kadbb9f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:summarize-agent-duotone-bold" /></template>
<style>
.f0wh-k8gw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 17h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ifhv18rgk {
  d: path("M12 12h6");
}

.ip7qw0c-r {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pi0o-3bfc {
  d: path("M12 7h9");
}

.pxx-spbdi {
  d: path("M7.5 8.83a3.5 3.5 0 1 1 -2.96 0");
}

.rpr8skgtq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 7h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t_kadbb9f {
  d: path("M12 17h3");
}

.um_bubczs {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7.5 8.83a3.5 3.5 0 1 1 -2.96 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
