<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrtyddbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pinch-zoom-out-sharp" /></template>
<style>
.yrtyddbmc {
  fill: currentColor;
  d: path("M1 12V7h1.5v2.45l2.975-2.975l1.05 1.05L3.55 10.5H6V12zm6.525-5.475l-1.05-1.05L9.45 2.5H7V1h5v5h-1.5V3.55zM13.575 23L7.6 17l1.575-1.625l2.825.8V7h2v8h1v-4h2v4h1v-3h2v3h1v-1h2v9z");
}

</style>
