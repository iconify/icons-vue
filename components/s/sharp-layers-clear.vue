<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h76wohbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-layers-clear" /></template>
<style>
.h76wohbze {
  fill: currentColor;
  d: path("m21 9l-9-7l-2.59 2.02l7.87 7.87zm0 5.07l-1.63-1.27l-.67.52l1.43 1.43zM3.41.86L2 2.27l4.22 4.22L3 9l9 7l2.1-1.63l1.42 1.42l-3.53 2.75l-7.37-5.73L3 14.07l9 7l4.95-3.85L20.73 21l1.41-1.41z");
}

</style>
