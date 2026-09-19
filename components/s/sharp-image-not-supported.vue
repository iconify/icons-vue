<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8fjy-48u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-image-not-supported" /></template>
<style>
.n8fjy-48u {
  fill: currentColor;
  d: path("m21.9 21.9l-8.49-8.49L3 3l-.9-.9L.69 3.51L3 5.83V21h15.17l2.31 2.31zM5 18l3.5-4.5l2.5 3.01L12.17 15l3 3zm16 .17L5.83 3H21z");
}

</style>
