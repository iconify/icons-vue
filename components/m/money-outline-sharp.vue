<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t579iybth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:money-outline-sharp" /></template>
<style>
.t579iybth {
  fill: currentColor;
  d: path("M14 16h5V8h-5zm2-2v-4h1v4zm-8 2h5V8H8zm2-2v-4h1v4zm-5 2h2V8H5zm-3 4V4h20v16zM4 6v12zm0 12h16V6H4z");
}

</style>
