<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h7vr07ufd"/><path class="xaz90clio"/><path class="ah2gkhstn"/><path class="f3be8jb4e"/><path class="b6a_ln9rl"/><path class="k6nj2fbya"/><path class="rkhcgsbdl"/><path class="o759xmblc"/><path class="wew0vnk_n"/><path class="k7cz9qivc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:normalize-data-duotone-bold" /></template>
<style>
.ah2gkhstn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.b6a_ln9rl {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 11v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f3be8jb4e {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h7vr07ufd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.k7cz9qivc {
  d: path("M18 11v5");
}

.o759xmblc {
  d: path("M6 8v8");
}

.rkhcgsbdl {
  d: path("M3 19h18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wew0vnk_n {
  d: path("M12 5v14");
}

.xaz90clio {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
