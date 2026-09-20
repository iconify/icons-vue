<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ab00fx-zf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slide-link-20-filled" /></template>
<style>
.ab00fx-zf {
  fill: currentColor;
  d: path("M13 11.5a.5.5 0 0 1 0 1h-.5a1.5 1.5 0 0 0 0 3h.5a.5.5 0 0 1 0 1h-.5a2.5 2.5 0 0 1 0-5zm3.5 0a2.5 2.5 0 0 1 0 5H16a.5.5 0 0 1 0-1h.5a1.5 1.5 0 0 0 0-3H16a.5.5 0 0 1 0-1zM15 4a3 3 0 0 1 3 3v3.836a3.5 3.5 0 0 0-1.5-.336h-4A3.5 3.5 0 0 0 9.628 16H5a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3zm1.5 9.5a.5.5 0 0 1 0 1h-4a.5.5 0 0 1 0-1z");
}

</style>
