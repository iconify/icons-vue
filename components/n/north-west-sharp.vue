<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibepfewaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:north-west-sharp" /></template>
<style>
.ibepfewaa {
  fill: currentColor;
  d: path("M18.6 20L7 8.4V15H5V5h10v2H8.4L20 18.6z");
}

</style>
