<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyuh8e0re"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:water-damage-outline-sharp" /></template>
<style>
.kyuh8e0re {
  fill: currentColor;
  d: path("M7 18h10V9.325L12 5.5L7 9.325zm-2 2v-9.15L2.2 13l-1.175-1.575L12 3l11 8.4l-1.2 1.6l-2.8-2.15V20zm8.413-4.587Q14 14.825 14 14q0-.675-.375-1.437T12 10q-1.25 1.8-1.625 2.563T10 14q0 .825.588 1.413T12 16t1.413-.587M12 14");
}

</style>
