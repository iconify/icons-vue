<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdidfdc2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:person-cane-fill-sharp" /></template>
<style>
.bdidfdc2c {
  fill: currentColor;
  d: path("M6.158 4.779a2 2 0 1 1 3.684-1.558A2 2 0 0 1 6.158 4.78M9 8.434l4.514 2.709a1 1 0 0 1 .318.302l6 9a1 1 0 0 1-1.664 1.11l-5.875-8.813L9 10.766v3.029l2.919 6.811a.999.999 0 1 1-1.838.788L8 16.539l-2.081 4.855a.999.999 0 1 1-1.838-.788L7 13.795V8a1 1 0 0 1 2 0Z");
}

</style>
