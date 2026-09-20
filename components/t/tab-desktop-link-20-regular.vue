<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j96d_l0gh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tab-desktop-link-20-regular" /></template>
<style>
.j96d_l0gh {
  fill: currentColor;
  d: path("M2.996 5.5a2.5 2.5 0 0 1 2.5-2.5h9a2.5 2.5 0 0 1 2.5 2.5v7.535A3.5 3.5 0 0 0 16.5 13h-.504V7h-6.5a1.5 1.5 0 0 1-1.5-1.5V4h-2.5a1.5 1.5 0 0 0-1.5 1.5v9a1.5 1.5 0 0 0 1.5 1.5h3.54a3.5 3.5 0 0 0 0 1h-3.54a2.5 2.5 0 0 1-2.5-2.5zm13 .5v-.5a1.5 1.5 0 0 0-1.5-1.5h-5.5v1.5a.5.5 0 0 0 .5.5zM12.5 14a2.5 2.5 0 0 0 0 5h.5a.5.5 0 0 0 0-1h-.5a1.5 1.5 0 0 1 0-3h.5a.5.5 0 0 0 0-1zm3.5 0a.5.5 0 0 0 0 1h.5a1.5 1.5 0 0 1 0 3H16a.5.5 0 0 0 0 1h.5a2.5 2.5 0 0 0 0-5zm-4 2.5a.5.5 0 0 1 .5-.5h4a.5.5 0 0 1 0 1h-4a.5.5 0 0 1-.5-.5");
}

</style>
