<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ih8wnhbbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:picture-in-picture-mobile-outline-rounded" /></template>
<style>
.ih8wnhbbo {
  fill: currentColor;
  d: path("M19 19.385q0 .69-.462 1.153T17.384 21H6.616q-.691 0-1.153-.462T5 19.385V4.615q0-.69.463-1.152T6.616 3h10.769q.69 0 1.153.463T19 4.616zm-1 0V4.615q0-.23-.192-.423T17.384 4H6.616q-.231 0-.424.192T6 4.615v14.77q0 .23.192.423t.423.192h10.77q.23 0 .423-.192t.192-.424M18 4H6zm-1.038 7.885V5.807q0-.348-.23-.578T16.154 5h-4.077q-.348 0-.578.23t-.23.578v6.077q0 .348.23.578t.578.23h4.077q.348 0 .578-.23t.23-.578m-1-.193h-3.693V6h3.692z");
}

</style>
