<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w46j4zb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:perm-device-information-sharp" /></template>
<style>
.w46j4zb4k {
  fill: currentColor;
  d: path("M11 16.5V11h2v5.5zM12 9q-.425 0-.712-.288T11 8t.288-.712T12 7t.713.288T13 8t-.288.713T12 9M5 23V1h14v22zm2-5h10V6H7z");
}

</style>
