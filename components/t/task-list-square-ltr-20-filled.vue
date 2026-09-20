<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f0eiwzbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:task-list-square-ltr-20-filled" /></template>
<style>
.f0eiwzbpx {
  fill: currentColor;
  d: path("M3 6a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3zm6.354 1.104a.5.5 0 0 0-.708-.708L7.234 7.808l-.397-.362a.5.5 0 0 0-.674.738l.75.685a.5.5 0 0 0 .69-.016zm0 4.292a.5.5 0 0 0-.708 0l-1.412 1.412l-.397-.362a.5.5 0 0 0-.674.738l.75.685a.5.5 0 0 0 .69-.015l1.75-1.75a.5.5 0 0 0 0-.707M11 12a.5.5 0 0 0 0 1h2.5a.5.5 0 0 0 0-1zm-.5-4.5a.5.5 0 0 0 .5.5h2.5a.5.5 0 0 0 0-1H11a.5.5 0 0 0-.5.5");
}

</style>
