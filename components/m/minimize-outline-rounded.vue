<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t36ia7ujy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:minimize-outline-rounded" /></template>
<style>
.t36ia7ujy {
  fill: currentColor;
  d: path("M7 21q-.425 0-.712-.288T6 20t.288-.712T7 19h10q.425 0 .713.288T18 20t-.288.713T17 21z");
}

</style>
