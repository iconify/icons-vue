<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l3xw66b6n"/><path class="rz5fyzc3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nabla" /></template>
<style>
.l3xw66b6n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.229 6.499C28.956 3.53 7.087 8.162 4.752 15.239c-2.406 7.437 12.991 27.167 22.434 27.174c9.322-1.37 23.49-30.186 12.043-35.914M11.29 16.718l22.733-2.374l-8.888 20.452zm19.261.424l-13.26 1.384l8.128 10.324z");
}

.rz5fyzc3f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.338 13.533a1.466 1.466 0 0 1 2.92-.165c.046.463-.1.92-.42 1.2c-.593.52-2.5 1.922-2.5 1.922h2.929");
}

</style>
