<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxglovfdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:panorama-horizontal-rounded" /></template>
<style>
.wxglovfdn {
  fill: currentColor;
  d: path("M3 20q-.425 0-.712-.288T2 19V5q0-.425.288-.712T3 4q.2 0 .888.238t1.837.512t2.713.513T12 5.5t3.563-.238t2.712-.512t1.838-.513T21 4q.425 0 .713.288T22 5v14q0 .425-.288.713T21 20q-.2 0-.888-.238t-1.837-.512t-2.712-.513T12 18.5t-3.562.238t-2.713.512t-1.837.513T3 20");
}

</style>
