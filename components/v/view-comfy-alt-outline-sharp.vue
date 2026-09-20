<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9ti8abbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-comfy-alt-outline-sharp" /></template>
<style>
.p9ti8abbd {
  fill: currentColor;
  d: path("M2 10V2h8v8zm2-2h4V4H4zM2 22v-8h8v8zm2-2h4v-4H4zm10-10V2h8v8zm2-2h4V4h-4zm-2 14v-8h8v8zm2-2h4v-4h-4zm0-4");
}

</style>
