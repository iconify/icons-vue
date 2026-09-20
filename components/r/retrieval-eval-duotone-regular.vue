<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vxtvt1e5w"/><path class="qa-jr78us"/><path class="d2e-bwu6v"/><path class="a-b09pbxz"/><path class="ox-vsbb8w"/><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="ymk1v8j2l"/><path class="lyy2bnbbp"/><path class="mrbwrkdfc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:retrieval-eval-duotone-regular" /></template>
<style>
.a-b09pbxz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10 7 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d2e-bwu6v {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m6.5 10 2 2L11 9.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ffw_pwyfz {
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
}

.kfdmhd64i {
  d: path("m15 15 6 6");
}

.lyy2bnbbp {
  d: path("m10 7 4 4");
}

.mrbwrkdfc {
  d: path("m14 7 -4 4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ox-vsbb8w {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m14 7 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qa-jr78us {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15 15 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vxtvt1e5w {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ymk1v8j2l {
  d: path("m6.5 10 2 2L11 9.5");
}

</style>
