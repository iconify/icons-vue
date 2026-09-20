<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b27te5b-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-connect" /></template>
<style>
.b27te5b-b {
  fill: currentColor;
  d: path("M15.182 17.184Q16.5 15.868 16.5 14v-4q0-1.868-1.315-3.184Q13.869 5.5 12.003 5.5T8.818 6.816T7.5 10v4q0 1.868 1.316 3.184Q10.13 18.5 11.997 18.5t3.185-1.316m-5.663-.705Q8.5 15.46 8.5 14v-4q0-1.458 1.022-2.48q1.021-1.02 2.48-1.02t2.479 1.02T15.5 10v4q0 1.458-1.022 2.48q-1.021 1.02-2.48 1.02t-2.479-1.02m3.02-6.94q.23-.23.23-.54t-.23-.54T12 8.23t-.54.23t-.23.54t.23.54t.54.23t.54-.23M5.616 22q-.667 0-1.141-.475T4 20.386V3.615q0-.666.475-1.14T5.615 2h12.77q.666 0 1.14.475T20 3.614v16.77q0 .666-.475 1.14t-1.14.475z");
}

</style>
