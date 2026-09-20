<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lon7_6b7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:north-west-rounded" /></template>
<style>
.lon7_6b7f {
  fill: currentColor;
  d: path("M7 8.4V14q0 .425-.288.713T6 15t-.712-.288T5 14V6q0-.425.288-.712T6 5h8q.425 0 .713.288T15 6t-.288.713T14 7H8.4l10.9 10.9q.275.275.275.7t-.275.7t-.7.275t-.7-.275z");
}

</style>
