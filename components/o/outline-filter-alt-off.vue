<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cz-0rqbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-filter-alt-off" /></template>
<style>
.cz-0rqbsm {
  fill: currentColor;
  d: path("m16.95 6l-3.57 4.55l1.43 1.43c1.03-1.31 4.98-6.37 4.98-6.37A.998.998 0 0 0 19 4H6.83l2 2zM2.81 2.81L1.39 4.22L10 13v6c0 .55.45 1 1 1h2c.55 0 1-.45 1-1v-2.17l5.78 5.78l1.41-1.41z");
}

</style>
