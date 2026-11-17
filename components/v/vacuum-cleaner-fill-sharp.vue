<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3_a51bgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:vacuum-cleaner-fill-sharp" /></template>
<style>
.z3_a51bgo {
  fill: currentColor;
  d: path("M6 12.099V8c0-2.35 1.681-4.087 3.9-4.599c.965-.223 2.006-.204 2.938.148c.991.375 1.772 1.12 2.111 2.135L19.721 20H21a1 1 0 0 1 0 2h-5a1 1 0 0 1 0-2h1.613L13.051 6.316c-.358-1.073-1.766-1.182-2.701-.967c-.625.145-1.227.449-1.671.917A2.47 2.47 0 0 0 8 8v4.099A5.01 5.01 0 0 1 12 17v4a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-4a5.01 5.01 0 0 1 4-4.901");
}

</style>
