<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c97-iorxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slide-arrow-forward-24-regular" /></template>
<style>
.c97-iorxt {
  fill: currentColor;
  d: path("M17.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m1.75-8A2.75 2.75 0 0 1 22 6.75v6.062a6.5 6.5 0 0 0-1.5-1.079V6.75c0-.69-.56-1.25-1.25-1.25H4.75c-.69 0-1.25.56-1.25 1.25v10.5c0 .69.56 1.25 1.25 1.25h6.327c.081.523.224 1.026.422 1.5H4.75A2.75 2.75 0 0 1 2 17.25V6.75A2.75 2.75 0 0 1 4.75 4zm.104 10.647a.5.5 0 1 0-.707.707l.646.646H17.25A3.25 3.25 0 0 0 14 19.25v.25a.5.5 0 0 0 1 0v-.25A2.25 2.25 0 0 1 17.25 17h2.043l-.646.646a.5.5 0 1 0 .707.707l1.5-1.5a.5.5 0 0 0 0-.707zM12.024 14a6.5 6.5 0 0 0-.71 1.5H6.75a.75.75 0 0 1 0-1.5zm3.226-3c.212 0 .402.089.538.23a6.5 6.5 0 0 0-2.44 1.27H6.75a.75.75 0 0 1 0-1.5zm-4-3a.75.75 0 0 1 0 1.5h-4.5a.75.75 0 0 1 0-1.5z");
}

</style>
