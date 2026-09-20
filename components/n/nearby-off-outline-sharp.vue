<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dp6gwdbth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nearby-off-outline-sharp" /></template>
<style>
.dp6gwdbth {
  fill: currentColor;
  d: path("m17.666 15.327l-.916-.915l2.43-2.431l-7.2-7.2l-2.45 2.45l-.914-.915L11.98 2.95l9.03 9.03zm-5.691 5.679l-9.02-9.02L6.528 8.41L2.65 4.528l.708-.708l16.746 16.747l-.702.701l-3.833-3.832zm.006-1.825l2.673-2.662l-1.848-1.848l-.825.825l-3.51-3.51l.825-.824l-1.842-1.843l-2.667 2.668zm2.927-6.612l-3.516-3.515l.57-.57L15.477 12z");
}

</style>
