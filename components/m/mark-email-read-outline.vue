<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="raabbuh_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mark-email-read-outline" /></template>
<style>
.raabbuh_h {
  fill: currentColor;
  d: path("m15.489 21.27l-3.558-3.558l.708-.708l2.85 2.85l5.688-5.688l.708.707zM12 11l7.692-5H4.308zm0 1.116L4 6.885v10.5q0 .269.173.442t.443.173H9.4l1 1H4.616q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v4.926l-1 1V6.885zm0 0");
}

</style>
