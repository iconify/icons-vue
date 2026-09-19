<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fiskdw5sq"/><path class="s5ebtjbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:read-you" /></template>
<style>
.fiskdw5sq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.709 19.87c-.626-1.787 8.072-1.458 12.558-2.234l16.338 11.707c5.756 18.124.809 14.27-9.951 6.652l-10.005-7.237c-4.918-4.39-10.282-8.287-8.94-8.887Z");
}

.s5ebtjbvo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.267 17.636c-.496.835 3.21-11.99 6.238-12.626c3.067 1.014 4.812 7.796 6.719 12.037c6.343.53 12.399.017 13.146 2.363c1.142 1.951-5.476 7.709-9.766 9.933m-20.594-.798c-3.426 12.563-2.718 13.165-1.396 14.187c1.964 1.72 11.47-5.692 12.43-6.45");
}

</style>
