<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnn_w164m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:task" /></template>
<style>
.fnn_w164m {
  fill: currentColor;
  d: path("m10.95 18l5.65-5.65l-1.45-1.45l-4.225 4.225l-2.1-2.1L7.4 14.45zM6 22q-.825 0-1.412-.587T4 20V4q0-.825.588-1.412T6 2h8l6 6v12q0 .825-.587 1.413T18 22zm7-13h5l-5-5z");
}

</style>
