<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ips7mzh_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:presence-away-24-filled" /></template>
<style>
.ips7mzh_z {
  fill: currentColor;
  d: path("M12 24c6.627 0 12-5.373 12-12S18.627 0 12 0S0 5.373 0 12s5.373 12 12 12m1-17.5v4.81l2.976 2.551a1.5 1.5 0 0 1-1.952 2.278l-3.5-3A1.5 1.5 0 0 1 10 12V6.5a1.5 1.5 0 0 1 3 0");
}

</style>
