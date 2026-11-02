<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnltg8b7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:navigation-fill" /></template>
<style>
.nnltg8b7s {
  fill: currentColor;
  d: path("M18.316 7.051c.392.131.754.338 1.066.609c.584.506 1.041 1.28.917 2.077c-.078.503-.398.93-.852 1.157l-5.702 2.851l-2.851 5.702a1.56 1.56 0 0 1-1.157.852c-.797.124-1.571-.333-2.077-.917a3.2 3.2 0 0 1-.609-1.066l-4-12a2.582 2.582 0 0 1 3.265-3.265Z");
}

</style>
