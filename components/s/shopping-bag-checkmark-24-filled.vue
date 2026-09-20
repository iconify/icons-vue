<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ve7z4bb6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:shopping-bag-checkmark-24-filled" /></template>
<style>
.ve7z4bb6u {
  fill: currentColor;
  d: path("M7 5v2H5.5A1.5 1.5 0 0 0 4 8.5V18a4 4 0 0 0 4 4h4.81A6.48 6.48 0 0 1 11 17.5a6.48 6.48 0 0 1 2-4.69V5c0-.334-.055-.656-.156-.956A1.5 1.5 0 0 1 15.5 5v2h-1v4.732a6.5 6.5 0 0 1 3-.732c.886 0 1.73.177 2.5.498V8.5A1.5 1.5 0 0 0 18.5 7H17V5a3 3 0 0 0-5-2.236A3 3 0 0 0 7 5m1.5 0a1.5 1.5 0 1 1 3 0v2h-3zM23 17.5a5.5 5.5 0 1 1-11 0a5.5 5.5 0 0 1 11 0m-2.146-2.354a.5.5 0 0 0-.708 0L16.5 18.793l-1.646-1.647a.5.5 0 0 0-.708.708l2 2a.5.5 0 0 0 .708 0l4-4a.5.5 0 0 0 0-.708");
}

</style>
