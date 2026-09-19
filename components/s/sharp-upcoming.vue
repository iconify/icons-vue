<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayhk6eozp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-upcoming" /></template>
<style>
.ayhk6eozp {
  fill: currentColor;
  d: path("m21.16 7.26l-1.41-1.41l-3.56 3.55l1.41 1.41s3.45-3.52 3.56-3.55M11 3h2v5h-2zm-4.6 7.81L7.81 9.4L4.26 5.84L2.84 7.26c.11.03 3.56 3.55 3.56 3.55M22 12h-7c0 1.66-1.34 3-3 3s-3-1.34-3-3H2v9h20z");
}

</style>
