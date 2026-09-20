<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trpap2bvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:steps-sharp" /></template>
<style>
.trpap2bvd {
  fill: currentColor;
  d: path("M20.5 22L7.4 9.5H1.9l5.8-7.775l3.3 1.65V6.65l3.675-.875l2.2 6.675L22 17.575L21.25 22zm-7.875 0L1.075 11.5h5.55L17.575 22z");
}

</style>
