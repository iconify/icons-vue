<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="jtrq17bci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:star-off-28-filled" /></template>
<style>
.jtrq17bci {
  fill: currentColor;
  d: path("M3.28 2.22a.75.75 0 1 0-1.06 1.06l6.297 6.298l-4.526.657c-1.19.173-1.664 1.635-.803 2.473l4.354 4.245l-1.028 5.993c-.203 1.184 1.04 2.087 2.104 1.528L14 21.644l5.382 2.83c1.063.56 2.307-.344 2.103-1.529l-.082-.481l3.316 3.317a.75.75 0 0 0 1.061-1.061zm7.566 5.444l9.679 9.68l-.067-.391l4.354-4.245c.86-.838.385-2.3-.804-2.473l-6.017-.874L15.3 3.908c-.532-1.077-2.069-1.077-2.6 0z");
}

</style>
