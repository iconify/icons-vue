<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8gqgc8lr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-layers" /></template>
<style>
.l8gqgc8lr {
  fill: currentColor;
  d: path("m11.99 18.54l-7.37-5.73L3 14.07l9 7l9-7l-1.63-1.27zM12 16l7.36-5.73L21 9l-9-7l-9 7l1.63 1.27zm0-11.47L17.74 9L12 13.47L6.26 9z");
}

</style>
