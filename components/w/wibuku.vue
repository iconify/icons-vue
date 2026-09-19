<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tibv-mb0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wibuku" /></template>
<style>
.tibv-mb0e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 10.145l10.88 27.454l3.967-9.312l-5.856-14.494zm39 .256L32.62 37.855l-3.967-9.311l5.856-14.495zm-23.854 8.223l4.277 10.612l4.027-10.544l-4.027 1.697z");
}

</style>
