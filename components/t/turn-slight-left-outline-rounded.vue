<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gpsxb7c2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:turn-slight-left-outline-rounded" /></template>
<style>
.gpsxb7c2a {
  fill: currentColor;
  d: path("M13.643 19.626q-.143-.144-.143-.357v-6.561q0-.116-.039-.221t-.134-.202L7.712 6.689v2.48q0 .213-.144.357q-.144.143-.357.143t-.356-.143t-.144-.357V5.808q0-.343.233-.576T7.519 5h3.362q.212 0 .356.144t.144.357t-.144.356t-.356.143H8.4l5.621 5.602q.217.217.348.518t.131.632v6.517q0 .213-.144.357t-.357.143t-.356-.143");
}

</style>
