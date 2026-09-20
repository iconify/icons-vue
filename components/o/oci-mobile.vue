<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z4wooftbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:oci-mobile" /></template>
<style>
.z4wooftbp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.499 8.5c7.18 0 13 6.94 13 15.5s-5.82 15.5-13 15.5H17.5c-4.644 0-8.936-2.954-11.258-7.75a18.11 18.11 0 0 1 0-15.5C8.564 11.454 12.856 8.5 17.5 8.5Z");
}

</style>
