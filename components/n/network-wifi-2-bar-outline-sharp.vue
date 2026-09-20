<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhk1a3kfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:network-wifi-2-bar-outline-sharp" /></template>
<style>
.dhk1a3kfs {
  fill: currentColor;
  d: path("M12 19.577L1.423 9q2.15-1.93 4.837-2.966Q8.946 5 12 5q3.06 0 5.746 1.035T22.577 9zm-4.525-5.952q.95-.7 2.1-1.088T12 12.15t2.425.388t2.1 1.087L21.1 9.05q-1.95-1.475-4.262-2.262T12 6t-4.837.788T2.9 9.05z");
}

</style>
