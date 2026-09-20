<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0jgz8cvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:receipt-outline-sharp" /></template>
<style>
.d0jgz8cvw {
  fill: currentColor;
  d: path("M4 20.77V3.23l1.27.962l1.346-.961l1.346.961l1.346-.961l1.346.961L12 3.231l1.346.961l1.346-.961l1.346.961l1.346-.961l1.347.961L20 3.231v17.538l-1.27-.961l-1.346.961l-1.346-.961l-1.346.961l-1.346-.961l-1.346.961l-1.346-.961l-1.346.961l-1.346-.961l-1.346.961l-1.347-.961zm2.5-4.885h11v-1h-11zm0-3.385h11v-1h-11zm0-3.384h11v-1h-11zM5 19.1h14V4.9H5zM5 4.9v14.2z");
}

</style>
