<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b0wupnb9n"/><path class="a5oa7lbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:metlife" /></template>
<style>
.a5oa7lbsn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.208 41.168h22.184a2.11 2.11 0 0 0 2.108-2.109V8.162a1.33 1.33 0 0 0-1.454-1.323c-12.74 1.235-22.838 18.445-22.838 31.373z");
}

.b0wupnb9n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.792 41.168H7.608a2.11 2.11 0 0 1-2.108-2.11V8.162a1.33 1.33 0 0 1 1.454-1.323c12.74 1.235 22.838 18.445 22.838 31.373z");
}

</style>
