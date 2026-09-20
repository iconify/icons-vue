<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h7vr07ufd"/><path class="eb8o-4buj"/><path class="hy5sozq_t"/><path class="doi_mob1c"/><path class="jdsld8y3d"/><path class="k6nj2fbya"/><path class="d223d_x9q"/><path class="zrdou8b0n"/><path class="uxy9sxbfx"/><path class="wgmfnvzml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tokenizer-duotone-bold" /></template>
<style>
.d223d_x9q {
  d: path("M3 12h6");
}

.doi_mob1c {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 19h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.eb8o-4buj {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h7vr07ufd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hy5sozq_t {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 12h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jdsld8y3d {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 19h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uxy9sxbfx {
  d: path("M3 19h10");
}

.wgmfnvzml {
  d: path("M16 19h5");
}

.zrdou8b0n {
  d: path("M12 12h9");
}

</style>
