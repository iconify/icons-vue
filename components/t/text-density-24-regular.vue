<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s03tsps0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-density-24-regular" /></template>
<style>
.s03tsps0r {
  fill: currentColor;
  d: path("M12.25 2a.75.75 0 0 1 .75.75v18.5a.75.75 0 0 1-1.5 0V2.75a.75.75 0 0 1 .75-.75M10 5H2.75a.75.75 0 0 0 0 1.5H10zm0 4H2.75a.75.75 0 0 0 0 1.5H10zm0 4H2.75a.75.75 0 0 0 0 1.5H10zm0 4H2.75a.75.75 0 0 0 0 1.5H10zm9.75 1H14.5v-1.5h5.25a.75.75 0 0 0 0-1.5H14.5v-1.5h5.25a2.25 2.25 0 0 1 0 4.5m0-7.5H14.5V9h5.25a.75.75 0 0 0 0-1.5H14.5V6h5.25a2.25 2.25 0 0 1 0 4.5");
}

</style>
