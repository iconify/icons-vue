<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nb_w41b1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:warning-lock-open-20-regular" /></template>
<style>
.nb_w41b1m {
  fill: currentColor;
  d: path("M18 10a2 2 0 0 1 2 2a.5.5 0 0 1-1 0a1 1 0 0 0-2 0v1h1a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-5a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1h3v-1a2 2 0 0 1 2-2M7.37 3.556c1.14-2.074 4.12-2.074 5.259 0l3.398 6.186a3 3 0 0 0-.676.848l-3.598-6.553c-.76-1.383-2.746-1.382-3.506 0L2.751 14.042c-.732 1.333.232 2.963 1.753 2.963H11v1H4.504c-2.281 0-3.727-2.445-2.629-4.444zM15.5 15.25a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5m-5.5-2.5a.75.75 0 1 1-.001 1.501A.75.75 0 0 1 10 12.75m0-6.25a.5.5 0 0 1 .5.5v4a.5.5 0 0 1-1 0V7a.5.5 0 0 1 .5-.5");
}

</style>
