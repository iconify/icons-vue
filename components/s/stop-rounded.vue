<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkipa4bvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stop-rounded" /></template>
<style>
.gkipa4bvu {
  fill: currentColor;
  d: path("M7 15.385v-6.77q0-.666.475-1.14T8.615 7h6.77q.666 0 1.14.475T17 8.615v6.77q0 .666-.475 1.14t-1.14.475h-6.77q-.666 0-1.14-.475T7 15.386");
}

</style>
