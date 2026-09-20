<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mq9ey5hdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:number-circle-7-20-filled" /></template>
<style>
.mq9ey5hdi {
  fill: currentColor;
  d: path("M2 10a8 8 0 1 1 16 0a8 8 0 0 1-16 0m5.5-4a.5.5 0 0 0 0 1h4.076a20.3 20.3 0 0 0-2.569 6.916a.5.5 0 1 0 .986.168a19.3 19.3 0 0 1 1.743-5.299c.319-.64.613-1.14.827-1.48a11 11 0 0 1 .318-.48l.017-.022l.003-.004A.501.501 0 0 0 12.5 6z");
}

</style>
