<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6exvzlxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-sidebar-outline-sharp" /></template>
<style>
.j6exvzlxw {
  fill: currentColor;
  d: path("M2 20V4h20v16zM17.5 8.675H20V6h-2.5zm0 4.65H20v-2.65h-2.5zM4 18h11.5V6H4zm13.5 0H20v-2.675h-2.5z");
}

</style>
