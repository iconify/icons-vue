<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="li4sxsbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:ribbon-12-filled" /></template>
<style>
.li4sxsbhp {
  fill: currentColor;
  d: path("M6 8a3.5 3.5 0 1 0 0-7a3.5 3.5 0 0 0 0 7m0 1c.729 0 1.412-.195 2-.535V10.5a.5.5 0 0 1-.777.416L6 10.101l-1.223.815A.5.5 0 0 1 4 10.5V8.465C4.588 8.805 5.271 9 6 9");
}

</style>
