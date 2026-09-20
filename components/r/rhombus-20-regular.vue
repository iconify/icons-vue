<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pd0o--5fv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rhombus-20-regular" /></template>
<style>
.pd0o--5fv {
  fill: currentColor;
  d: path("M4.89 4.296A2 2 0 0 1 6.76 3h10.237a2 2 0 0 1 1.872 2.704l-3.76 10A2 2 0 0 1 13.238 17H3.001a2 2 0 0 1-1.872-2.704zM6.76 4a1 1 0 0 0-.936.648l-3.76 10A1 1 0 0 0 3.001 16h10.237a1 1 0 0 0 .936-.648l3.76-10A1 1 0 0 0 16.998 4z");
}

</style>
