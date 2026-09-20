<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vj3sgbb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:spo2-sharp" /></template>
<style>
.vj3sgbb5p {
  fill: currentColor;
  d: path("M11 20v-6h4.5v6zm1.5-1.5H14v-3h-1.5zM17 22v-3.75h3v-.75h-3V16h4.5v3.75h-3v.75h3V22zm-8-.05q-3.075-.35-5.038-2.637T2 13.8q0-2.5 1.988-5.437T10 2q3.3 2.8 5.238 5.3T17.75 12H9z");
}

</style>
