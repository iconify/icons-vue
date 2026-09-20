<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="za1o8i3ss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:snippet-folder-sharp" /></template>
<style>
.za1o8i3ss {
  fill: currentColor;
  d: path("M2 20V4h8l2 2h10v14zm12.5-4.5v-5h1.375l1.625 1.625V15.5zM13 17h6v-5.5L16.5 9H13z");
}

</style>
