<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h4gumgb9f"/><path class="zesrtccnv"/><path class="acx2mjbnt"/><path class="o1-mr2bqb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:passkey-outline-bold" /></template>
<style>
.acx2mjbnt {
  d: path("M12 11v6");
}

.h4gumgb9f {
  d: path("M7 5a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
}

.o1-mr2bqb {
  d: path("M12 15h3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.zesrtccnv {
  d: path("M10 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
