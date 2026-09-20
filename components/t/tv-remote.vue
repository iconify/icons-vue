<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tms994cap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tv-remote" /></template>
<style>
.tms994cap {
  fill: currentColor;
  d: path("M14.125 14.125Q15 13.25 15 12t-.875-2.125T12 9t-2.125.875T9 12t.875 2.125T12 15t2.125-.875M9.615 22q-.69 0-1.152-.462T8 20.385V3.615q0-.69.463-1.152T9.616 2h4.769q.69 0 1.153.463T16 3.616v16.769q0 .69-.462 1.153T14.385 22zm1.496-9.11q-.361-.361-.361-.89t.36-.89q.361-.36.89-.36t.89.36q.36.361.36.89t-.36.89q-.361.36-.89.36t-.89-.36m1.41-7.37q.21-.21.21-.52t-.21-.52t-.52-.21t-.52.21t-.21.52t.21.52t.52.21t.52-.21");
}

</style>
