<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hsnj9o-9y"/><path class="puskh763k"/><path class="b577pibsg"/><path class="jzwk6ubza"/><path class="sh-bzloxt"/><path class="jkuojibnm"/><path class="d1du4rxru"/><path class="a9cczt5un"/><path class="t3w_facee"/><path class="j4if4rbfv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:softmax-duotone-thin" /></template>
<style>
.a9cczt5un {
  d: path("M10 8v12");
}

.b577pibsg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d1du4rxru {
  d: path("M6 14v6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hsnj9o-9y {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j4if4rbfv {
  d: path("M18 14v6");
}

.jkuojibnm {
  d: path("M3 20h18");
}

.jzwk6ubza {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 3v17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.puskh763k {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 14v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sh-bzloxt {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 14v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t3w_facee {
  d: path("M14 3v17");
}

</style>
