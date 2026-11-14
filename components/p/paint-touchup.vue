<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dc2ziobgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:paint-touchup" /></template>
<style>
.dc2ziobgp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.894 4.106q.586.586.586 1.414q0 .829-.586 1.414l-3.889 3.889q-.333.334-.745.477q.506 1.529-1.023 3.058l-1.061 1.061q-2.297 2.297-4.595 0t0-4.595l1.061-1.061Q10.171 8.234 11.7 8.74q.143-.412.477-.745l3.889-3.889q.585-.586 1.414-.586q.828 0 1.414.586M6.1 16.3l1.5 2q.023.031.043.064q1.093 1.819-.525 3.193t-3.236 0t-.525-3.193q.02-.033.043-.064l1.5-2q.044-.059.099-.108q.055-.05.119-.087q.063-.038.133-.063q.07-.024.143-.034t.147-.007t.145.022q.072.019.138.051t.126.076q.086.064.15.15");
}

</style>
