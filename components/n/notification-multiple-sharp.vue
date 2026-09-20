<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_xn7qb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:notification-multiple-sharp" /></template>
<style>
.p_xn7qb_z {
  fill: currentColor;
  d: path("M1 22V7h2v13h15v2zm4-4V6.3L14 1l2 1.175L7.2 7.35l6.8 4l7.5-4.45l1.5.9V18zm8.85-8l-2.8-2.8l1.4-1.4l1.4 1.4l3.55-3.55l1.4 1.4z");
}

</style>
