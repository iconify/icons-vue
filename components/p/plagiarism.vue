<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynqk4bb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:plagiarism" /></template>
<style>
.ynqk4bb2p {
  fill: currentColor;
  d: path("M11.066 15.923q.488 0 .935-.151q.447-.15.841-.414l2.72 2.719l.707-.708l-2.719-2.719q.302-.375.434-.832t.132-.945q0-1.238-.872-2.094t-2.128-.856t-2.13.871q-.87.871-.87 2.129t.855 2.129t2.095.871m-1.36-1.591q-.59-.592-.59-1.409t.59-1.408t1.41-.592t1.408.592q.592.59.592 1.408t-.592 1.409t-1.408.591q-.818 0-1.41-.591M6.617 21q-.691 0-1.153-.462T5 19.385V4.615q0-.69.463-1.152T6.616 3H14.5L19 7.5v11.885q0 .69-.462 1.153T17.384 21zM14 8h4l-4-4z");
}

</style>
