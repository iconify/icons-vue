<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mwm320bqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:shade" /></template>
<style>
.mwm320bqt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.98 5.945L4.5 24.968h5.571v17.087h9.296V30.232h9.266v11.823h9.296V24.968H43.5z");
}

</style>
