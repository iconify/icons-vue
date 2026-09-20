<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u51p9sbgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slide-arrow-forward-20-filled" /></template>
<style>
.u51p9sbgk {
  fill: currentColor;
  d: path("M14.5 10a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m1.604 1.896a.5.5 0 1 0-.707.707l.896.897H14.75A2.75 2.75 0 0 0 12 16.25v.25a.5.5 0 0 0 1 0v-.25c0-.966.784-1.75 1.75-1.75h1.543l-.896.896a.5.5 0 1 0 .707.707l1.752-1.751A.5.5 0 0 0 18 14a.5.5 0 0 0-.146-.354zM15.5 4A2.5 2.5 0 0 1 18 6.5v3.757A5.48 5.48 0 0 0 14.5 9c-.818 0-1.593.18-2.291.5H5.5a.5.5 0 0 0 0 1h5.227c-.455.43-.837.937-1.125 1.5H5.5a.5.5 0 0 0 0 1h3.708a5.5 5.5 0 0 0 0 3H4.5A2.5 2.5 0 0 1 2 13.5v-7A2.5 2.5 0 0 1 4.5 4zm-10 3a.5.5 0 0 0 0 1h4a.5.5 0 0 0 0-1z");
}

</style>
