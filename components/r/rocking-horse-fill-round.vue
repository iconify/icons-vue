<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ll__06pbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rocking-horse-fill-round" /></template>
<style>
.ll__06pbv {
  fill: currentColor;
  d: path("m4.532 15.241l1.388-4.164l-.367-.735l-1.106.552a1 1 0 0 1-1.341-.447l-1-2a1 1 0 0 1 0-.894l2-4A1 1 0 0 1 5 3a7.006 7.006 0 0 1 6.93 6H18a2 2 0 0 0 2-2a1 1 0 0 1 2 0a3.98 3.98 0 0 1-1.172 2.828a3.98 3.98 0 0 1-2.506 1.159l1.2 4.198q.365-.382.689-.799a1 1 0 1 1 1.578 1.228a12.3 12.3 0 0 1-2.175 2.175a12.3 12.3 0 0 1-4.351 2.176h-.002a12.4 12.4 0 0 1-10.875-2.176h-.001v-.001a12.3 12.3 0 0 1-2.174-2.174a1 1 0 1 1 1.578-1.228q.348.448.743.855m8.687.759h-2.438l-.562 2.248c1.178.205 2.384.205 3.562 0Z");
}

</style>
