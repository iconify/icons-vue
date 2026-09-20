<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sfz-ptbjp"/><path class="cwy7f6b5v"/><path class="s5lrmxbhj"/><path class="j2n-bbcgq"/><path class="oitoahb9q"/><path class="mlzwc7b5b"/><path class="kd8pirhpr"/><path class="crw18vrkk"/><path class="z-xixkiyt"/><path class="hspeog_hs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:recycle-duotone-regular" /></template>
<style>
.crw18vrkk {
  d: path("m18 14 -5 5H9");
}

.cwy7f6b5v {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12.5 6.5 15 9l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hspeog_hs {
  d: path("m7 18 -4 -4 4 -4");
}

.j2n-bbcgq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11.5 16.5 9 19l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kd8pirhpr {
  d: path("M12.5 6.5 15 9l-2.5 2.5");
}

.mlzwc7b5b {
  d: path("m6 14 5 -5h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oitoahb9q {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m7 18 -4 -4 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s5lrmxbhj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m18 14 -5 5H9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sfz-ptbjp {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m6 14 5 -5h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z-xixkiyt {
  d: path("M11.5 16.5 9 19l2.5 2.5");
}

</style>
