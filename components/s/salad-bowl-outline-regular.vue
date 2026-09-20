<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xi253xtcz"/><path class="nt880jc9g"/><path class="ikvwkzeey"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:salad-bowl-outline-regular" /></template>
<style>
.ikvwkzeey {
  d: path("M12 12c0 -3 2 -6 5 -7 1 3 -1 6 -5 7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nt880jc9g {
  d: path("M12 12c0 -4 -2 -7 -5 -8 -1 4 1 7 5 8");
}

.xi253xtcz {
  d: path("M4 12h16c0 5 -4 9 -8 9s-8 -4 -8 -9");
}

</style>
