<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmhw7gazp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-phone-enabled" /></template>
<style>
.zmhw7gazp {
  fill: currentColor;
  d: path("m3 15.46l5.27-.61l2.52 2.52c2.83-1.44 5.15-3.75 6.59-6.59l-2.53-2.53l.61-5.25h5.51C21.55 13.18 13.18 21.55 3 20.97z");
}

</style>
