<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="jln0nhtuh"/><g class="n1mjunbsu"><path class="auqb8ebvb"/><path class="rupa39b7a"/><path class="qcoj20bsx"/><circle class="rn33qlbzs"/><path class="s0dsslb3y"/><path class="bgunnhbba"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:wheelchair-symbol" /></template>
<style>
.auqb8ebvb {
  d: path("M32.14 32.834a4.527 4.527 0 0 1-9.055 0V20.077a4.529 4.529 0 0 1 9.055 0z");
}

.bgunnhbba {
  d: path("m44.837 43.37l-.208.87C42.936 51.339 36.67 56.3 29.393 56.3c-8.654 0-15.694-7.04-15.694-15.694c0-5.42 2.769-10.386 7.406-13.285l.235-.146v-4l-.729.377c-6.434 3.324-10.43 9.86-10.43 17.06c0 10.594 8.619 19.213 19.214 19.213c8.314 0 15.641-5.332 18.232-13.269l.096-.292l-2.886-2.885");
}

.jln0nhtuh {
  fill: var(--svg-color--1b75bb, #1b75bb);
  d: path("M64 57.1c0 3.811-3.087 6.9-6.896 6.9H6.894a6.9 6.9 0 0 1-6.896-6.9V6.9A6.9 6.9 0 0 1 6.894.002h50.21C60.914.002 64 3.092 64 6.9z");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.qcoj20bsx {
  d: path("M52.51 47.617c-1.104.639-2.604.105-3.354-1.186c-.746-1.291-.459-2.858.645-3.496l5.635-3.263c1.104-.639 2.605-.104 3.355 1.185c.746 1.295.457 2.857-.646 3.498z");
}

.rn33qlbzs {
  cx: 27.07px;
  cy: 9.304px;
  r: 4.62px;
}

.rupa39b7a {
  d: path("M30.804 27.597c-1.76 0-3.187-.997-3.187-2.225s1.427-2.224 3.187-2.224h8.979c1.76 0 3.188.996 3.188 2.224s-1.428 2.225-3.188 2.225zM43.4 35.871c-.846-1.518-.385-3.386 1.029-4.172c1.414-.788 3.248-.199 4.092 1.316l4.311 7.734c.846 1.518.381 3.385-1.031 4.174c-1.414.787-3.246.197-4.092-1.318z");
}

.s0dsslb3y {
  d: path("M48.36 33.975a3.387 3.387 0 0 1-3.385 3.387h-17.09a3.387 3.387 0 0 1 0-6.773h17.09a3.385 3.385 0 0 1 3.385 3.386");
}

</style>
