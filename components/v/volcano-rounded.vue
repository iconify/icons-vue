<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-apznzye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:volcano-rounded" /></template>
<style>
.d-apznzye {
  fill: currentColor;
  d: path("M19.35 22H5.075q-1.1 0-1.688-.9t-.137-1.9l2.225-5q.25-.55.738-.875T7.3 13H9l1.5-3.75q.225-.575.725-.912T12.35 8h4.15q.675 0 1.2.4t.725 1.05l2.85 10q.275.95-.325 1.75t-1.6.8M13 4V2q0-.425.288-.712T14 1t.713.288T15 2v2q0 .425-.288.713T14 5t-.712-.288T13 4m3.825.775L18.25 3.35q.275-.275.688-.275t.712.275q.3.3.3.7t-.3.7l-1.425 1.425q-.275.275-.688.288t-.712-.288q-.275-.275-.275-.7t.275-.7m-7.05 1.4L8.35 4.75q-.275-.275-.275-.687t.275-.713q.3-.3.7-.3t.7.3l1.425 1.425q.275.275.287.688t-.287.712q-.275.275-.7.275t-.7-.275");
}

</style>
