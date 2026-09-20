<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uu5iixt_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:square-shadow-24-filled" /></template>
<style>
.uu5iixt_a {
  fill: currentColor;
  d: path("M13.75 2A3.25 3.25 0 0 1 17 5.25V7h1.75A3.25 3.25 0 0 1 22 10.25v8A3.75 3.75 0 0 1 18.25 22h-8A3.25 3.25 0 0 1 7 18.75V17H5.25A3.25 3.25 0 0 1 2 13.75v-8.5A3.25 3.25 0 0 1 5.25 2zm-8.5 2C4.56 4 4 4.56 4 5.25v8.5c0 .69.56 1.25 1.25 1.25h8.5c.69 0 1.25-.56 1.25-1.25v-8.5C15 4.56 14.44 4 13.75 4z");
}

</style>
