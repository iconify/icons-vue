<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dngj2nb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:shield-checkmark-16-filled" /></template>
<style>
.dngj2nb1h {
  fill: currentColor;
  d: path("M7.647 2.146a.5.5 0 0 1 .708 0C9.595 3.39 10.969 4 12.5 4a.5.5 0 0 1 .5.5v1.1a5.5 5.5 0 0 0-7.496 7.204C3.844 11.589 3 9.81 3 7.5v-3a.5.5 0 0 1 .5-.5c1.53 0 2.904-.611 4.147-1.854M15 10.5a4.5 4.5 0 1 0-9 0a4.5 4.5 0 0 0 9 0m-2.146-1.854a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708 0l-1-1a.5.5 0 0 1 .708-.708l.646.647l2.646-2.647a.5.5 0 0 1 .708 0");
}

</style>
