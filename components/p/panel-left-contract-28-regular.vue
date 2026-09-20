<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="fcj6w9z4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:panel-left-contract-28-regular" /></template>
<style>
.fcj6w9z4f {
  fill: currentColor;
  d: path("M17.28 11.53a.75.75 0 1 0-1.06-1.06l-3 3a.75.75 0 0 0 0 1.06l3 3a.75.75 0 1 0 1.06-1.06l-1.72-1.72h5.69a.75.75 0 0 0 0-1.5h-5.69zM26 7.75A3.75 3.75 0 0 0 22.25 4H5.755a3.75 3.75 0 0 0-3.75 3.75v12.5A3.75 3.75 0 0 0 5.754 24H22.25A3.75 3.75 0 0 0 26 20.25zM22.25 5.5a2.25 2.25 0 0 1 2.25 2.25v12.5a2.25 2.25 0 0 1-2.25 2.25H11.006v-17zm-12.745 0v17H5.754a2.25 2.25 0 0 1-2.25-2.25V7.75a2.25 2.25 0 0 1 2.25-2.25z");
}

</style>
