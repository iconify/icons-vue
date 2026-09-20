<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="pyoyb9bti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:star-28-filled" /></template>
<style>
.pyoyb9bti {
  fill: currentColor;
  d: path("M12.701 3.908c.532-1.078 2.069-1.078 2.6 0l2.692 5.452l6.017.875c1.19.173 1.664 1.634.804 2.473l-4.355 4.244l1.028 5.993c.204 1.185-1.04 2.088-2.103 1.529l-5.382-2.83l-5.382 2.83c-1.064.559-2.307-.344-2.104-1.529l1.028-5.993l-4.355-4.244c-.86-.839-.385-2.3.804-2.473l6.017-.875z");
}

</style>
