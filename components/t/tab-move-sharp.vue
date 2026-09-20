<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rr0u9ac-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tab-move-sharp" /></template>
<style>
.rr0u9ac-d {
  fill: currentColor;
  d: path("M3 21v-5h2v3h14V7H5v3H3V3h18v18zm8.5-3.5l-1.4-1.4l2.075-2.1H3v-2h9.175L10.1 9.9l1.4-1.4L16 13z");
}

</style>
