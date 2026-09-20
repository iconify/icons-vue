<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gl4u2dd9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stat-minus-2-rounded" /></template>
<style>
.gl4u2dd9k {
  fill: currentColor;
  d: path("m12 16.175l3.9-3.875q.275-.275.688-.288t.712.288q.275.275.275.7t-.275.7l-3.875 3.875q-.575.575-1.425.575t-1.425-.575L6.7 13.7q-.275-.275-.288-.687T6.7 12.3q.275-.275.7-.275t.7.275zm0-6L15.9 6.3q.275-.275.688-.287t.712.287q.275.275.275.7t-.275.7l-3.875 3.875q-.575.575-1.425.575t-1.425-.575L6.7 7.7q-.275-.275-.288-.687T6.7 6.3q.275-.275.7-.275t.7.275z");
}

</style>
