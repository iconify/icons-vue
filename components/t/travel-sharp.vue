<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghy0l8-el"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:travel-sharp" /></template>
<style>
.ghy0l8-el {
  fill: currentColor;
  d: path("m9.925 21.125l-2.475-4.6l-4.6-2.475l1.775-1.75l3.625.625l2.55-2.55L2.875 7l2.1-2.15l9.625 1.7l3.1-3.1q.575-.575 1.425-.575t1.425.575t.575 1.412t-.575 1.413L17.425 9.4l1.7 9.6L17 21.125L13.6 13.2l-2.55 2.55l.65 3.6z");
}

</style>
