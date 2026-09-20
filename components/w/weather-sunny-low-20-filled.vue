<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pdny5dbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:weather-sunny-low-20-filled" /></template>
<style>
.pdny5dbvw {
  fill: currentColor;
  d: path("M5.662 11a4.481 4.481 0 1 1 8.746 0H17.5a.5.5 0 0 1 0 1h-15a.5.5 0 0 1 0-1zm4.473 7a.5.5 0 0 1-.22 0zM5.076 4.382l-.069-.058a.5.5 0 0 0-.638.765l.858.858l.07.058a.5.5 0 0 0 .638-.765zm10.663.637a.5.5 0 0 0-.765-.637l-.859.858l-.058.07a.5.5 0 0 0 .765.637l.859-.858zM10.52 2.435a.5.5 0 0 0-.992.09v1.213l.008.09a.5.5 0 0 0 .992-.09V2.524zM8.5 16a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1zM5 14a.5.5 0 0 1 .5-.5h9a.5.5 0 0 1 0 1h-9A.5.5 0 0 1 5 14");
}

</style>
