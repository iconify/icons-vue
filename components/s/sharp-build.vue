<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="orxwvpbnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-build" /></template>
<style>
.orxwvpbnk {
  fill: currentColor;
  d: path("M12.09 2.91C10.08.9 7.07.49 4.65 1.67l4.34 4.34l-3 3l-4.34-4.34C.48 7.1.89 10.09 2.9 12.1a6.51 6.51 0 0 0 6.89 1.48l9.82 9.82l3.71-3.71l-9.78-9.79c.92-2.34.44-5.1-1.45-6.99");
}

</style>
