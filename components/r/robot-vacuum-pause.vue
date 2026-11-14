<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ahq5g9jjl"/><path class="kdavt3bku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:robot-vacuum-pause" /></template>
<style>
.ahq5g9jjl {
  d: path("M2.5 7.25a8.5 3.5 0 1 0 17 0a8.5 3.5 0 1 0-17 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kdavt3bku {
  d: path("M2.5 7.25v3q0 .086.01.172t.031.171q.02.086.051.171t.071.169t.092.167q.05.084.111.166t.131.163t.15.16t.169.157t.188.154q.098.076.205.149q.108.074.224.145q.115.072.24.141t.256.135q.133.067.273.13q.14.064.288.125t.302.118t.316.113q.161.054.329.105q.167.051.341.099q.173.048.352.092t.363.085t.373.077t.381.07q.193.032.389.061q.197.029.397.054q.199.025.402.046q.202.021.407.038t.411.029t.414.021t.416.013t.417.004q1.059 0 2.085-.107t1.957-.314m1.929-.588q.3-.122.569-.255q.269-.134.504-.277q.236-.144.436-.296q.2-.153.362-.313q.163-.16.286-.326t.206-.336t.124-.342q.042-.173.042-.346v-3M2.5 17.5h11.4m2.85-2v6m3.5-6v6");
}

</style>
