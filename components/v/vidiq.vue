<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="um3k_2bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vidiq" /></template>
<style>
.um3k_2bsf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.194 34.526L5.5 39.39V8.61l11.694 4.864m16.83 7L42.5 24l-8.644 3.596M12.038 14.234v19.01m19.114.001l-6.46-6.222m-.002-12.789zc3.58 0 6.462 2.809 6.462 6.297v6.416c0 3.49-2.881 6.298-6.46 6.298s-6.462-2.809-6.462-6.298v-6.416c0-3.488 2.881-6.297 6.46-6.297");
}

</style>
