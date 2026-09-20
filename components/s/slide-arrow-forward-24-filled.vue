<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9zemebwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slide-arrow-forward-24-filled" /></template>
<style>
.w9zemebwd {
  fill: currentColor;
  d: path("M17.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m1.75-8A2.75 2.75 0 0 1 22 6.75v6.062A6.48 6.48 0 0 0 17.5 11c-.593 0-1.166.08-1.712.23a.75.75 0 0 0-.538-.23h-8.5a.75.75 0 0 0 0 1.5h6.598a6.5 6.5 0 0 0-1.324 1.5H6.75a.75.75 0 0 0 0 1.5h4.565a6.5 6.5 0 0 0-.315 2c0 .886.178 1.73.499 2.5H4.75A2.75 2.75 0 0 1 2 17.25V6.75A2.75 2.75 0 0 1 4.75 4zm.104 10.647a.5.5 0 1 0-.707.707l.646.646H17.25A3.25 3.25 0 0 0 14 19.25v.25a.5.5 0 0 0 1 0v-.25A2.25 2.25 0 0 1 17.25 17h2.043l-.646.646a.5.5 0 1 0 .707.707l1.5-1.5a.5.5 0 0 0 0-.707zM6.75 8a.75.75 0 0 0 0 1.5h4.5a.75.75 0 0 0 0-1.5z");
}

</style>
