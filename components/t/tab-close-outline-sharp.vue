<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="um9mw3b1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tab-close-outline-sharp" /></template>
<style>
.um9mw3b1t {
  fill: currentColor;
  d: path("m11.9 13.5l2.1-2.1l2.1 2.1l1.4-1.4l-2.1-2.1l2.1-2.1l-1.4-1.4L14 8.6l-2.1-2.1l-1.4 1.4l2.1 2.1l-2.1 2.1zM6 18V2h16v16zm2-2h12V4H8zm-6 6V6h2v14h14v2zm6-6V4z");
}

</style>
