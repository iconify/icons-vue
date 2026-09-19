<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y-xs7rbme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:switch-phone" /></template>
<style>
.y-xs7rbme {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.882 4.5a3.767 3.767 0 0 0-3.774 3.775v10.678c2.787 1.755 6.903 2.964 10.068 2.903v-2.94L33.01 24.24l-10.834 5.325v-2.939c-3.165-.062-7.28 1.146-10.068 2.9v10.2a3.767 3.767 0 0 0 3.774 3.774h16.236a3.767 3.767 0 0 0 3.774-3.775V8.275A3.767 3.767 0 0 0 32.118 4.5zm5.364 3.578h5.508");
}

</style>
