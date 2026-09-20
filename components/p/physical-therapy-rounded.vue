<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fp6ymyqaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:physical-therapy-rounded" /></template>
<style>
.fp6ymyqaa {
  fill: currentColor;
  d: path("M14.625 21.925q.25.1.488.063t.437-.163t.325-.337T16 21v-3q0-.425-.288-.712T15 17H9.375q-.575 0-.937.35t-.438.8t.138.875t.762.625zM19.225 11q.725 0 1.25.488T21 12.7q0 .575-.325 1.05t-.875.675L18 15H9.375q-1.425 0-2.4.975T6 18.375q0 .45.125.863T6.45 20H4q-.425 0-.712-.288T3 19v-3q0-2.075 1.463-3.537T8 11zm-6.4-7.825Q14 4.35 14 6t-1.175 2.825T10 10T7.175 8.825T6 6t1.175-2.825T10 2t2.825 1.175");
}

</style>
