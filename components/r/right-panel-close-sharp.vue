<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="om7i8tbvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:right-panel-close-sharp" /></template>
<style>
.om7i8tbvs {
  fill: currentColor;
  d: path("m7.5 16l4-4l-4-4zM5 19h9V5H5zm-2 2V3h18v18z");
}

</style>
