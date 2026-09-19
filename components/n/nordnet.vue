<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dc0ceq_sb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nordnet" /></template>
<style>
.dc0ceq_sb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.15 17.35h10.1v13.3l11.65-13.3h5.6l-11.65 13.3h-10.1v-13.3L10.1 30.65H4.5Zm0 0");
}

</style>
