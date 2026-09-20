<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h5dixub9x"/><path class="xu7yp0bop"/><path class="czolrj_qt"/><path class="gz0v-hb-h"/><path class="wioyn1brg"/><path class="l4mvwmb8t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:open-book-duotone-regular" /></template>
<style>
.czolrj_qt {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15 17 2 2 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gz0v-hb-h {
  d: path("M12 8Q9 5 3 5v12q6 0 9 3");
}

.h5dixub9x {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 8Q9 5 3 5v12q6 0 9 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l4mvwmb8t {
  d: path("m15 17 2 2 4 -4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wioyn1brg {
  d: path("M12 8q3 -3 9 -3v12q-6 0 -9 3");
}

.xu7yp0bop {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 8q3 -3 9 -3v12q-6 0 -9 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
