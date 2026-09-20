<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryr3ux5mi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-quilt-sharp" /></template>
<style>
.ryr3ux5mi {
  fill: currentColor;
  d: path("M9.325 11.5V5H21v6.5zm6.35 7.5v-6.5H21V19zm-6.35 0v-6.5h5.35V19zM3 19V5h5.325v14z");
}

</style>
