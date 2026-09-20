<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3yk2rz4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:play-for-work-outline-rounded" /></template>
<style>
.i3yk2rz4p {
  fill: currentColor;
  d: path("M8.075 18.588Q6.4 17.175 6.075 15q-.05-.4.225-.7T7 14t.713.213t.362.562Q8.35 16.2 9.463 17.1T12 18t2.538-.9t1.387-2.325q.075-.35.363-.562T17 14t.7.3t.225.7q-.325 2.175-2 3.588T12 20t-3.925-1.412M11 11.15V6q0-.425.288-.712T12 5t.713.288T13 6v5.15l.9-.9q.3-.3.7-.288t.7.313q.275.3.287.7t-.287.7l-2.6 2.6q-.15.15-.325.213T12 14.55t-.375-.062t-.325-.213l-2.6-2.6q-.275-.275-.275-.687t.275-.713q.3-.3.713-.3t.712.3z");
}

</style>
