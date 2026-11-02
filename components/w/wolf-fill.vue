<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pci3h1biy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wolf-fill" /></template>
<style>
.pci3h1biy {
  fill: currentColor;
  d: path("m20.414 13l1.293 1.293a1 1 0 0 1-.336 1.635l-4.647 1.859l-.83 1.66C15.357 20.522 14.348 21.999 13 22h-2c-1.348-.001-2.357-1.478-2.894-2.553l-.83-1.66l-4.647-1.859a1 1 0 0 1-.336-1.635L3.586 13l-1.293-1.293a1 1 0 0 1 0-1.414l1-1C3.605 8.98 4 8.468 4 8V4a1.25 1.25 0 0 1 .14-.582c.371-.712 1.242-.835 1.932-.549c.237.098.453.242.635.424l2 2C9.02 5.605 9.532 6 10 6h4c.468 0 .98-.395 1.293-.707l2-2c.182-.182.398-.326.635-.424c.69-.286 1.561-.163 1.932.549c.093.18.141.379.14.582v4c0 .468.395.98.707 1.293l1 1a1 1 0 0 1 0 1.414ZM9.707 10.293a.999.999 0 1 0-1.414 1.414l1 1a.999.999 0 1 0 1.414-1.414Zm6 1.414a.999.999 0 1 0-1.414-1.414l-1 1a.999.999 0 1 0 1.414 1.414ZM12.01 17H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
