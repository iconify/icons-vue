<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gvsw63w8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-alt-text-20-filled" /></template>
<style>
.gvsw63w8y {
  fill: currentColor;
  d: path("M13 9h4V8h-4zm-4 7.5V13H8v4h1.05a2.5 2.5 0 0 1-.05-.5M11.5 9h.5V8H8v4h1v-.5A2.5 2.5 0 0 1 11.5 9M7 12V8H3v4zm-4 1h4v4H5.5A2.5 2.5 0 0 1 3 14.5zm10-6h4V5.5A2.5 2.5 0 0 0 14.5 3H13zm-1-4v4H8V3zM7 3v4H3V5.5A2.5 2.5 0 0 1 5.5 3zm3 8.5a1.5 1.5 0 0 1 1.5-1.5h6a1.5 1.5 0 0 1 1.5 1.5v5a1.5 1.5 0 0 1-1.5 1.5h-6a1.5 1.5 0 0 1-1.5-1.5zm7 4a.5.5 0 0 0-.5-.5h-4a.5.5 0 0 0 0 1h4a.5.5 0 0 0 .5-.5M12.5 12a.5.5 0 0 0 0 1h4a.5.5 0 0 0 0-1z");
}

</style>
