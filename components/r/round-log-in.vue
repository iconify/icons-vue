<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iegtfhz7v"/><path class="j-04fdb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-log-in" /></template>
<style>
.iegtfhz7v {
  fill: currentColor;
  d: path("M9 2h9c1.1 0 2 .9 2 2v16c0 1.1-.9 2-2 2H9c-1.1 0-2-.9-2-2v-1a1 1 0 0 1 2 0v1h9V4H9v1a1 1 0 1 1-2 0V4c0-1.1.9-2 2-2");
}

.j-04fdb4v {
  fill: currentColor;
  d: path("M10.795 16.295c.39.39 1.02.39 1.41 0l3.588-3.588a1 1 0 0 0 0-1.414l-3.588-3.588a.999.999 0 0 0-1.411 1.411L12.67 11H4a1 1 0 0 0 0 2h8.67l-1.876 1.884a1 1 0 0 0 .001 1.411");
}

</style>
