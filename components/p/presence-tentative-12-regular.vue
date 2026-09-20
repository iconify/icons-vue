<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="u9j211w9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:presence-tentative-12-regular" /></template>
<style>
.u9j211w9t {
  fill: currentColor;
  d: path("M12 6.055A6 6 0 0 1 6.057 12zm-.35-2.082a6 6 0 0 0-.844-1.568l-8.4 8.4c.474.354 1.001.64 1.569.844zM1.191 9.587a6 6 0 0 1-.84-1.561L8.027.35a6 6 0 0 1 1.562.84zM5.945 0A6 6 0 0 0 .001 5.944z");
}

</style>
