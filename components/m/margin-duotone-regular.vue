<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nywqkrldb"/><path class="twnn15b6d"/><path class="j57updd3h"/><path class="bo8u7q83r"/><path class="zrdou8b0n"/><path class="j8_8pdbyc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:margin-duotone-regular" /></template>
<style>
.bo8u7q83r {
  d: path("M21 12a9 9 0 1 1 -9 -9");
}

.j57updd3h {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 3v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j8_8pdbyc {
  d: path("M12 3v9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nywqkrldb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M21 12a9 9 0 1 1 -9 -9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.twnn15b6d {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 12h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zrdou8b0n {
  d: path("M12 12h9");
}

</style>
