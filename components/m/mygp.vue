<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kkn570b_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mygp" /></template>
<style>
.kkn570b_a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.948 19.402c.96.613.317 9.196 3.184 14.539c3.737 6.965 6.58 8.277 9.232 6.898s3.636-6.196.85-11.833c-4.047-8.184-11.568-10.087-10.93-11.819c.61-1.658 4.934-2.825 9.762-3.94s6.739-2.175 6.42-3.767s-2.918-3.608-8.49-2.123s-9.164 9.554-9.854 9.819s-7.92-.692-13.598 3.765s-5.836 8.012-3.926 9.339s4.987 1.061 7.481-2.175s7.818-10.011 9.87-8.703");
}

</style>
