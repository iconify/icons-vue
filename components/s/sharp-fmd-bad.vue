<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ay_iqabxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-fmd-bad" /></template>
<style>
.ay_iqabxu {
  fill: currentColor;
  d: path("M12 2c-4.2 0-8 3.22-8 8.2c0 3.32 2.67 7.25 8 11.8c5.33-4.55 8-8.48 8-11.8C20 5.22 16.2 2 12 2m1 13h-2v-2h2zm0-4h-2V6h2z");
}

</style>
