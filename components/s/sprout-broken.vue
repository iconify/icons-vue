<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c9a3g5qfi"/><path class="e5zbbmjev"/><path class="yqpbzab-z"/><path class="x4z9wr1fn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sprout-broken" /></template>
<style>
.c9a3g5qfi {
  d: path("M11.9668 20.669V10.869");
}

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

.x4z9wr1fn {
  d: path("M6.4668 21.669C9.4668 20.269 14.4668 20.269 17.4668 21.669");
}

.yqpbzab-z {
  d: path("M20.3394 3.89162C20.5141 4.38852 20.5369 4.98852 20.3668 5.66902C19.5668 8.86902 15.7668 10.869 11.9668 10.869C11.9668 6.46902 13.7668 3.26902 16.7668 2.46902C17.0513 2.39792 17.3273 2.35492 17.592 2.33832");
}

</style>
