<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7gf70b8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:screwdriver-fill-sharp" /></template>
<style>
.f7gf70b8u {
  fill: currentColor;
  d: path("m14.414 11l1.293 1.293a1 1 0 0 1 0 1.414l-7 7a3.828 3.828 0 0 1-5.414-5.414l7-7a1 1 0 0 1 1.414 0L13 9.586l6.293-6.293a.999.999 0 1 1 1.414 1.414Z");
}

</style>
