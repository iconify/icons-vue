<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_6d2uy7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:play-for-work-outline-sharp" /></template>
<style>
.p_6d2uy7n {
  fill: currentColor;
  d: path("M7.75 18.25Q6 16.5 6 14h2q0 1.65 1.175 2.825T12 18t2.825-1.175T16 14h2q0 2.5-1.75 4.25T12 20t-4.25-1.75M12 14.975l-4-4L9.4 9.55l1.6 1.6V5h2v6.15l1.6-1.6l1.4 1.425z");
}

</style>
