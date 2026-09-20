<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6nv5cb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:water-ec-sharp" /></template>
<style>
.a6nv5cb3i {
  fill: currentColor;
  d: path("M11.5 17.5h.23l2.943-5.192H12.5V8.5h-.23l-2.943 5.192H11.5zm-4.501 1.439Q5 16.877 5 13.8q0-2.154 1.738-4.765T12 3.308q3.525 3.117 5.262 5.728Q19 11.646 19 13.8q0 3.077-1.999 5.139T12 21t-5.001-2.061");
}

</style>
