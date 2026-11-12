<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jndp2ibsp"/><path class="ums6h4bgs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:translate-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jndp2ibsp {
  d: path("M12.7895 17.6667L11.5263 21M12.7895 17.6667H19.7368M12.7895 17.6667L14.01 14.4458M19.7368 17.6667L21 21M19.7368 17.6667L17.5314 11.8468C17.3389 11.3387 16.8316 11 16.2632 11C15.6948 11 15.1874 11.3387 14.9949 11.8468L14.01 14.4458M14.01 14.4458C12.5485 14.189 10.45 13.0468 8.632 11.6006M8.632 11.6006C6.6549 13.2474 4.4429 14.5 3 14.5M8.632 11.6006C7.1993 10.461 5.9408 9.1326 5.3056 7.9M8.632 11.6006C10.5068 10.0391 13 7.7563 13 5.1985M14.5789 5C14.5789 5 13.9254 5.0928 13 5.1985C11.7779 5.3381 10.0814 5.5 8.7895 5.5C6.5192 5.5 3 5 3 5M8.2632 3H9.3158");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ums6h4bgs {
  d: path("M19.7378 17.6667L17.5324 11.8468C17.3398 11.3387 16.8325 11 16.2641 11C15.6957 11 15.1884 11.3387 14.9958 11.8468L14.011 14.4458L12.7904 17.6667L11.5273 21M12.7904 17.6667H19.7378M19.7378 17.6667L21.001 21");
}

</style>
