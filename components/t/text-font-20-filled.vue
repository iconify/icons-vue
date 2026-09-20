<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d4l38cw3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-font-20-filled" /></template>
<style>
.d4l38cw3f {
  fill: currentColor;
  d: path("M5.999 2c.31 0 .59.192.7.482l2.27 5.939q.03.06.048.125l.037.099l-.793 2.127L7.776 9.5H4.221l-.772 2.021a.75.75 0 0 1-1.401-.536l3.25-8.503a.75.75 0 0 1 .7-.482M4.795 8h2.407L6 4.85zm7.908-2.51a.75.75 0 0 0-1.405 0L7.193 16.5h-.438a.75.75 0 0 0 0 1.5h2.5a.75.75 0 1 0 0-1.5h-.461l.747-2.003h4.919l.746 2.003h-.455a.75.75 0 0 0 0 1.5h2.5a.75.75 0 0 0 0-1.5h-.444zm1.197 7.507h-3.8L12 7.899z");
}

</style>
