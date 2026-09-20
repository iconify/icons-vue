<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="huymj2nsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-move-right-32-light" /></template>
<style>
.huymj2nsn {
  fill: currentColor;
  d: path("M29 3.5a.5.5 0 0 0-1 0v25a.5.5 0 0 0 1 0zm-3.146 12.146a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708-.708l2.147-2.146H17.5a.5.5 0 0 1 0-1h6.793l-2.147-2.146a.5.5 0 0 1 .708-.708zM21 3.5a.5.5 0 0 0-.5-.5h-13A4.5 4.5 0 0 0 3 7.5v17A4.5 4.5 0 0 0 7.5 29h13a.5.5 0 0 0 .5-.5v-8a.5.5 0 0 0-.5-.5H12v-8h8.5a.5.5 0 0 0 .5-.5zM12 11V4h8v7zm-1-7v7H4V7.5A3.5 3.5 0 0 1 7.5 4zM4 21h7v7H7.5A3.5 3.5 0 0 1 4 24.5zm8 7v-7h8v7zM4 12h7v8H4z");
}

</style>
