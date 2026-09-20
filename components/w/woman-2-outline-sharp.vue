<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y302akbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:woman-2-outline-sharp" /></template>
<style>
.y302akbqx {
  fill: currentColor;
  d: path("M10.5 22v-6H7l3.575-9h2.85L17 16h-3.5v6zM12 6q-.825 0-1.412-.587T10 4t.588-1.412T12 2t1.413.588T14 4t-.587 1.413T12 6");
}

</style>
