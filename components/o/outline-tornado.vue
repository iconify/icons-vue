<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ly7y3aczv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-tornado" /></template>
<style>
.ly7y3aczv {
  fill: currentColor;
  d: path("M23 3H1l11 19zm-3.47 2l-1.74 3H6.21L4.47 5zm-9.27 10h3.48L12 18.01zm4.64-2H9.1l-1.74-3h9.27z");
}

</style>
