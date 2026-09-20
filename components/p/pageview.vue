<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdi7cofcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pageview" /></template>
<style>
.wdi7cofcn {
  fill: currentColor;
  d: path("M9.725 13.275Q9 12.55 9 11.5t.725-1.775T11.5 9t1.775.725T14 11.5t-.725 1.775T11.5 14t-1.775-.725M4.615 19q-.69 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .544-.308.953t-.81.568l-5.466-5.467q.35-.506.467-.953q.117-.445.117-.986q0-1.452-1.024-2.476T11.5 8T9.024 9.024T8 11.5t1.024 2.476T11.5 15q.65 0 1.215-.204q.564-.204 1.031-.611L18.562 19z");
}

</style>
