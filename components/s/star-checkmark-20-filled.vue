<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wg3j57btc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:star-checkmark-20-filled" /></template>
<style>
.wg3j57btc {
  fill: currentColor;
  d: path("M10.898 2.9a1 1 0 0 0-1.794 0l-1.93 3.91l-4.317.628a1 1 0 0 0-.554 1.706l3.124 3.044l-.738 4.3a1 1 0 0 0 1.451 1.054l3.05-1.604a5.5 5.5 0 0 1 7.96-6.259l.549-.535a1 1 0 0 0-.554-1.706l-4.317-.627zM19 14.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-2.146-1.854a.5.5 0 0 0-.708 0L13.5 15.293l-.646-.647a.5.5 0 0 0-.708.708l1 1a.5.5 0 0 0 .708 0l3-3a.5.5 0 0 0 0-.708");
}

</style>
