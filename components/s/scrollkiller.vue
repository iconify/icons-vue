<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ij3d2-bhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:scrollkiller" /></template>
<style>
.ij3d2-bhd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.422 4.5v39h23.156v-39zm0 0l23.156 39m-23.156 0l23.156-39");
}

</style>
