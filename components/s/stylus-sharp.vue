<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynr7aybob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stylus-sharp" /></template>
<style>
.ynr7aybob {
  fill: currentColor;
  d: path("M8.45 20.1L2.7 21.3l1.2-5.75zm1.625-1.225l-4.95-4.95l11.75-11.75l4.95 4.95z");
}

</style>
