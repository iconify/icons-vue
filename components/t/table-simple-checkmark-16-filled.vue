<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fno-0mvbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-simple-checkmark-16-filled" /></template>
<style>
.fno-0mvbd {
  fill: currentColor;
  d: path("M8.5 14h3a2.5 2.5 0 0 0 2.5-2.5v-3H8.5zm0-6.5H14v-3A2.5 2.5 0 0 0 11.5 2h-3zM7.5 2v5.5H2v-3A2.5 2.5 0 0 1 4.5 2zM2 11.5v-3h5.5V14h-3A2.5 2.5 0 0 1 2 11.5m10.854-.646l-1.5 1.5a.5.5 0 0 1-.708 0l-.75-.75a.5.5 0 0 1 .708-.708l.396.397l1.146-1.147a.5.5 0 0 1 .708.708");
}

</style>
