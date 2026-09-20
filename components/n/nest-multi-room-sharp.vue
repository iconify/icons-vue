<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ef4fxjtok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:nest-multi-room-sharp" /></template>
<style>
.ef4fxjtok {
  fill: currentColor;
  d: path("m4 9l8-6l8 6zm0 12v-4h9v4zm11 0v-4h5v4zM4 15v-4h5v4zm7 0v-4h9v4z");
}

</style>
