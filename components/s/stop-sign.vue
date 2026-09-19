<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="j4tfmqqjn"/><path class="lzdhiubyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:stop-sign" /></template>
<style>
.j4tfmqqjn {
  fill: currentColor;
  d: path("M44.426 2H19.574L2 19.574v24.852L19.574 62h24.852L62 44.426V19.574zM60 43.598L43.598 60H20.402L4 43.598V20.402L20.402 4h23.195L60 20.402z");
}

.lzdhiubyb {
  fill: currentColor;
  d: path("M22.473 9L9 22.474v19.051L22.473 55h19.052L55 41.525V22.474L41.525 9z");
}

</style>
