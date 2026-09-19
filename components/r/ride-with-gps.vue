<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cjq8jsb3c"/><path class="tug_snbex"/><path class="ayw5xkbpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ride-with-gps" /></template>
<style>
.ayw5xkbpo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.319 21.586c-.534-.51-1.337-.57-2.123-.57c-4.79 0-8.696 3.906-8.696 8.696s3.907 8.696 8.696 8.696c1.16 0 2.268-.231 3.284-.642c3.648-1.354 6.617-6.637 7.413-10.39c.44-2.08-1.604-3.623-2.17-4.084c-.414-.336-2.617-1.53-3.594-2.425c-2.935-2.686-1.067-5.034-.591-5.615c2.288-2.79 8.24-2.569 9.148-2.52c.257 2.526 2.718 4.653 4.807 4.96c1.454.215 4.404.009 5.728-.678");
}

.cjq8jsb3c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.687 12.736c-2.009-.134-6.757 4.036-5.743 5.26l.02.02c.425.624 3.867 3.644 5.829 4.637c.01.005 1.11.557 1.275.583c.697.115 1.277-.45 1.616-.715a8.76 8.76 0 0 1 5.12-1.656c4.79 0 8.696 3.907 8.696 8.696s-3.867 8.696-8.657 8.696c-1.34 0-2.58-.473-3.715-1.019c-1.034-.496-1.867-1.358-2.547-2.3");
}

.tug_snbex {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.308 11.55c2.12-2.285 4.575-2.118 7.244-1.716c1.453.22 2.656 1.288 2.656 2.765c0 1.502-1.225 2.726-2.726 2.726s-2.726-1.224-2.726-2.726c0-.803.35-1.527.907-2.026c.483-.435 1.068-.756 1.766-.756");
}

</style>
