<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o02syqbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:personal-places-sharp" /></template>
<style>
.o02syqbjz {
  fill: currentColor;
  d: path("M7 19.5V5h8.558q.215 0 .39.105t.298.264L18.77 9l-2.523 3.63q-.123.16-.298.265t-.39.105H8v6.5z");
}

</style>
