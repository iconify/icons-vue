<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="toagqrlzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:plant-sick" /></template>
<style>
.toagqrlzc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.25 7.977V7.5q0-3.121 2.748-3.967q2.652-.816 4.297 1.44q1.646 1.294 1.766 3.518q.117 2.162-1.242 3.747q-.048.056-.106.102t-.124.079t-.137.053t-.144.026t-.147-.003t-.144-.032t-.135-.059t-.12-.085q-1.514-1.297-1.636-3.56q-.097-1.798.703-3.208q-.963-1.023-2.39-.584q-1.689.52-1.689 2.533v6.25h2.16q1.168 0 1.917.895q.75.896.544 2.045l-.625 3.5q-.368 2.06-2.461 2.06h-4.57q-2.093 0-2.461-2.06l-.625-3.5q-.206-1.149.544-2.045q.749-.895 1.917-.895h2.16v-2.584q-2.067 1.708-5.873 1.074q-.068-.012-.133-.035q-.07-.025-.133-.064q-.063-.038-.118-.088t-.098-.109t-.075-.127t-.048-.139q-.018-.071-.021-.145t.008-.147t.036-.142q.844-2.321 3.15-3.11q1.617-.553 3.305-.157");
}

</style>
