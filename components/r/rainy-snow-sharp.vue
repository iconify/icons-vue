<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8cgdt2mh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:rainy-snow-sharp" /></template>
<style>
.n8cgdt2mh {
  fill: currentColor;
  d: path("m7.78 18.677l-1.957-3.896l.896-.458l1.958 3.89zm9 0l-4.957-9.896l.896-.458l4.958 9.89zm-4.55-.157q-.21-.21-.21-.52t.21-.52t.52-.21t.52.21t.21.52t-.21.52t-.52.21t-.52-.21m9.55.157l-.957-1.896l.896-.458l.952 1.896zm-11-3L5.824 5.781l.896-.452l4.952 9.89zm8.7-1.157q-.21-.21-.21-.52t.21-.52t.52-.21t.52.21t.21.52t-.21.52t-.52.21t-.52-.21m-15-2q-.21-.21-.21-.52t.21-.52t.52-.21t.52.21t.21.52t-.21.52t-.52.21t-.52-.21m13.8-.843l-2.957-5.896l.896-.458l2.952 5.896zm-15-2L1.324 5.781l.896-.452l1.952 3.89zm7.45-3.157q-.21-.21-.21-.52t.21-.52t.52-.21t.52.21t.21.52t-.21.52t-.52.21t-.52-.21");
}

</style>
