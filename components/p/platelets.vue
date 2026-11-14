<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h94jqmb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:platelets" /></template>
<style>
.h94jqmb4s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 7.5q0-1.889 1.622-2.835q1.373-.801 3.084-.445q1.781-.589 3.134.272q1.553.988 1.177 2.999q.379 1.839-1.177 2.829q-1.299.827-3.046.46q-1.747.574-3.172-.257Q3.75 9.577 3.75 7.5m8.75 5.046q.018 1.843 1.434 2.873q1.333.97 3.066.601q1.786.375 3.064-.775q1.344-1.21.945-3.041q.176-1.842-1.229-2.846q-1.332-.95-3.064-.39q-1.575-.356-2.907.613q-1.521 1.106-1.309 2.965M3.25 17.5q0-1.881 1.584-2.937q1.411-.94 3.122-.592q1.739-.565 3.172.37q1.574 1.026 1.376 2.914q.188 2.001-1.339 3.129q-1.36 1.005-3.122.645q-1.728.551-3.227-.511Q3.25 19.409 3.25 17.5");
}

</style>
