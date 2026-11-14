<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kxzdfyjgv"/><path class="e5zbbmjev"/><path class="on_p-0b-l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sprout-line-duotone" /></template>
<style>
.e5zbbmjev {
  d: path("M11.9667 15.269C8.16685 15.269 4.16685 12.669 3.56685 9.46898C3.16685 7.26898 5.16685 6.26898 7.56675 6.96898C10.3667 7.76898 11.9667 10.869 11.9667 15.269Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kxzdfyjgv {
  d: path("M11.9668 20.669V20.619M11.9668 20.619V10.869M11.9668 20.619C9.9668 20.619 7.9668 20.969 6.4668 21.669M11.9668 20.619C13.9668 20.619 15.9668 20.969 17.4668 21.669");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.on_p-0b-l {
  d: path("M11.9668 10.869C11.9668 6.46903 13.7668 3.26902 16.7668 2.46902C19.1668 1.86902 20.9668 3.26902 20.3668 5.66902C19.5668 8.86902 15.7668 10.869 11.9668 10.869Z");
}

</style>
