<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ibuanu9pl"/><path class="s81hy6bws"/><path class="bh5bi6dfy"/><path class="tsm_xmb_i"/><path class="vqb4gsbju"/><path class="vce-1obpa"/><path class="az1hpy9gr"/><path class="gl3o38_gx"/><path class="lzdsnnb7v"/><path class="q3srlnbfr"/><path class="dzjr38hwz"/><path class="s74j1ubnz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wind-turbine-duotone-thin" /></template>
<style>
.az1hpy9gr {
  d: path("M12 9v12");
}

.bh5bi6dfy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 21h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dzjr38hwz {
  d: path("m13 9 5 5");
}

.gl3o38_gx {
  d: path("M8 21h8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ibuanu9pl {
  fill: currentColor;
  d: path("M11 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.lzdsnnb7v {
  d: path("M11 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.q3srlnbfr {
  d: path("M12 2v5");
}

.s74j1ubnz {
  d: path("m11 9 -5 5");
}

.s81hy6bws {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 9v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tsm_xmb_i {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 2v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vce-1obpa {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m11 9 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vqb4gsbju {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m13 9 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
