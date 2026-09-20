<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nt0735d7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:room-service-outline-sharp" /></template>
<style>
.nt0735d7w {
  fill: currentColor;
  d: path("M2 19v-2h20v2zm1-3v-1q0-3.2 1.963-5.65T10 6.25V4h4v2.25q3.1.65 5.05 3.1T21 15v1zm2.05-2h13.9q-.35-2.6-2.325-4.3T12 8T7.388 9.7T5.05 14M12 14");
}

</style>
