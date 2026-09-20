<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v40rrzbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:swipe-right-24-filled" /></template>
<style>
.v40rrzbnx {
  fill: currentColor;
  d: path("M6 12a1 1 0 0 0 1 1h11.585l-1.292 1.293a1 1 0 0 0-.083 1.32l.083.094a1 1 0 0 0 1.32.083l.094-.083l3-3a1 1 0 0 0 .083-1.32l-.083-.094l-3-3a1 1 0 0 0-1.497 1.32l.083.094L18.585 11H7a1 1 0 0 0-1 1m-4 0a5 5 0 0 0 9.584 2H9.872a3.5 3.5 0 1 1 0-4h1.712A5.001 5.001 0 0 0 2 12");
}

</style>
