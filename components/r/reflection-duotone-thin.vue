<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ug25h9bgu"/><path class="tyaw_2bqn"/><path class="sl6rqxyeh"/><path class="kdmyrxbfd"/><path class="uverd3z0e"/><path class="k3x4ygb5y"/><path class="r_je2bdjk"/><path class="xyf3o9drf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:reflection-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k3x4ygb5y {
  d: path("M15.5 5.94a7 7 0 0 1 0 12.12");
}

.kdmyrxbfd {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 15v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r_je2bdjk {
  d: path("M12 4v5");
}

.sl6rqxyeh {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 4v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tyaw_2bqn {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15.5 5.94a7 7 0 0 1 0 12.12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ug25h9bgu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8.5 18.06a7 7 0 0 1 0 -12.12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uverd3z0e {
  d: path("M8.5 18.06a7 7 0 0 1 0 -12.12");
}

.xyf3o9drf {
  d: path("M12 15v5");
}

</style>
