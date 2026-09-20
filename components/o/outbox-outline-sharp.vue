<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmq2fjbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:outbox-outline-sharp" /></template>
<style>
.mmq2fjbfx {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-1h14v-3.384h-3.577q-.557.95-1.46 1.475T12 17.616t-1.963-.525t-1.46-1.475H5zm8.725-2.934q.775-.55 1.075-1.45H19V5H5v9.616h4.2q.3.9 1.075 1.45t1.725.55t1.725-.55M5 19h14zm6.5-5.692V8.619l-2.1 2.1L8.692 10L12 6.692L15.308 10l-.708.72l-2.1-2.1v4.688z");
}

</style>
