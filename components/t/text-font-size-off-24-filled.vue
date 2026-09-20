<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehmcyttrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-font-size-off-24-filled" /></template>
<style>
.ehmcyttrn {
  fill: currentColor;
  d: path("M2.22 2.22a.75.75 0 0 1 1.06 0l18.5 18.5a.75.75 0 0 1-1.06 1.06l-6.28-6.28h-2.091l-1.41 3.845a1 1 0 0 1-1.87.017L8.343 17.5H4.656l-.724 1.862a1 1 0 0 1-1.864-.724l3.5-9l.066-.138a1 1 0 0 1 1.798.138l2.54 6.533l1.378-3.76l-9.13-9.13a.75.75 0 0 1 0-1.061M15.5 3a1 1 0 0 1 .939.655l5.5 15q.023.07.038.14L16.682 13.5h1.237L15.5 6.903l-1.453 3.962l-1.559-1.558l2.074-5.652l.064-.14A1 1 0 0 1 15.5 3M5.434 15.5h2.132L6.5 12.758z");
}

</style>
