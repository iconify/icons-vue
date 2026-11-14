<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fe_r_nnem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:rgb-lights" /></template>
<style>
.fe_r_nnem {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 8.5q0-2.589 1.831-4.419Q9.411 2.25 12 2.25t4.419 1.831T18.25 8.5q0 .375-.038.734q1.068.457 1.957 1.347Q22 12.411 22 15t-1.831 4.419t-4.419 1.831q-2.132 0-3.75-1.242q-1.618 1.242-3.75 1.242q-2.589 0-4.419-1.831Q2 17.589 2 15t1.831-4.419q.889-.89 1.957-1.347q-.038-.359-.038-.734");
}

</style>
