<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="f_v_dfbgn"/><path class="no6kjwbqz"/><path class="s1b0lnbma"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rabotcharge" /></template>
<style>
.f_v_dfbgn {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
}

.no6kjwbqz {
  d: path("M20.23 12.68a1.7 1.7 0 0 0-1.03.494l-6.79 7.24c-2.525 2.695-3.032 9.266 1.71 13.984c4.92 4.689 10.786 4.681 14.478 1.485l7.013-6.701c1.319-1.371-1.425-4.006-2.877-2.473l-6.699 6.385c-1.954 1.685-6.632 1.353-9.308-1.168c-2.493-2.14-3.436-7.473-.899-9.803l6.205-6.295c1.253-1.228-.268-3.297-1.802-3.148m-3.503 19.246l-2.608 2.473z");
}

.s1b0lnbma {
  d: path("M30.082 11.522c1.724-1.69 4.256.826 2.668 2.63l-4.292 4.446c-2.03 1.965-4.262-.848-2.59-2.552zm4.153 4.444c1.725-1.691 4.256.826 2.668 2.63l-4.292 4.446c-2.03 1.965-4.261-.848-2.59-2.552z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
