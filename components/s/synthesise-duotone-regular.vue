<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fzm6r7bhr"/><path class="jkka-vwvt"/><path class="nzx-eixar"/><path class="yu92orbma"/><path class="icy6dnbvy"/><path class="kv9cthbyn"/><path class="t51i6hb9i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:synthesise-duotone-regular" /></template>
<style>
.fzm6r7bhr {
  fill: currentColor;
  d: path("M6 17.5a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2V20a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.icy6dnbvy {
  d: path("M12 8v5");
}

.jkka-vwvt {
  d: path("M3 5h6");
}

.kv9cthbyn {
  d: path("m9 10 3 3 3 -3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nzx-eixar {
  d: path("M12 5h3");
}

.t51i6hb9i {
  d: path("M6 17.5a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2V20a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

.yu92orbma {
  d: path("M18 5h3");
}

</style>
