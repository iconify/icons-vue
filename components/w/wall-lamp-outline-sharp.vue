<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dt7u937gt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:wall-lamp-outline-sharp" /></template>
<style>
.dt7u937gt {
  fill: currentColor;
  d: path("M3 21v-6h2v6zm5.35-10h9.3l-1.8-6h-5.7zm0 0h9.3zM6 19v-2h6v-4H5.65l3-10h8.7l3 10H14v6z");
}

</style>
