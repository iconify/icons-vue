<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="v_lfbsbem"/><path class="hy5sozq_t"/><path class="t7m0hm6fo"/><path class="bo8u7q83r"/><path class="zrdou8b0n"/><path class="j8_8pdbyc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:margin-duotone-bold" /></template>
<style>
.bo8u7q83r {
  d: path("M21 12a9 9 0 1 1 -9 -9");
}

.hy5sozq_t {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 12h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j8_8pdbyc {
  d: path("M12 3v9");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t7m0hm6fo {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 3v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v_lfbsbem {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 12a9 9 0 1 1 -9 -9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zrdou8b0n {
  d: path("M12 12h9");
}

</style>
