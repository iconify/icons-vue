<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfk5zynne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:zoom-in-map" /></template>
<style>
.gfk5zynne {
  fill: currentColor;
  d: path("m3.9 21.5l-1.4-1.4L5.6 17H3v-2h6v6H7v-2.6zm16.2 0L17 18.4V21h-2v-6h6v2h-2.6l3.1 3.1zM3 9V7h2.6L2.5 3.9l1.4-1.4L7 5.6V3h2v6zm12 0V3h2v2.6l3.1-3.1l1.4 1.4L18.4 7H21v2z");
}

</style>
