<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sktojtbqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:rectangle-goggles-sharp-fill" /></template>
<style>
.sktojtbqy {
  fill: currentColor;
  d: path("M12 5L22 5C22.5523 5 23 5.4477 23 6L23 18C23 18.5523 22.5523 19 22 19L16 19C15.6962 19 15.4089 18.8619 15.2191 18.6247L12 14.6008L8.7809 18.6247C8.5911 18.8619 8.3038 19 8 19L2 19C1.4477 19 1 18.5523 1 18L1 6C1 5.4477 1.4477 5 2 5Z");
}

</style>
