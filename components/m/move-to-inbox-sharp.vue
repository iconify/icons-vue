<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8gns0bww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:move-to-inbox-sharp" /></template>
<style>
.t8gns0bww {
  fill: currentColor;
  d: path("m12 14l-4-4l1.4-1.45l1.6 1.6V6h2v4.15l1.6-1.6L16 10zm-9 7V3h18v18zm10.725-5.55Q14.5 14.9 14.8 14H19V5H5v9h4.2q.3.9 1.075 1.45T12 16t1.725-.55");
}

</style>
