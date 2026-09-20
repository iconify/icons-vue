<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bixxtzbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:network-wifi-3-bar-sharp" /></template>
<style>
.bixxtzbdb {
  fill: currentColor;
  d: path("M12 19.577L1.423 9q2.15-1.93 4.837-2.966Q8.946 5 12 5q3.06 0 5.746 1.035T22.577 9zM5.8 11.95q1.325-.95 2.9-1.487t3.3-.538t3.3.538t2.9 1.487l2.9-2.9q-1.95-1.475-4.262-2.262T12 6t-4.837.788T2.9 9.05z");
}

</style>
