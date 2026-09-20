<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpm928bxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tooltip" /></template>
<style>
.mpm928bxl {
  fill: currentColor;
  d: path("m12 21l-2.29-3.5H4.615q-.666 0-1.14-.475T3 15.886V4.615q0-.666.475-1.14T4.615 3h14.77q.666 0 1.14.475T21 4.615v11.27q0 .666-.475 1.14t-1.14.475H14.29z");
}

</style>
