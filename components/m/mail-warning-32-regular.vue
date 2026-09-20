<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k3wketq_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-warning-32-regular" /></template>
<style>
.k3wketq_b {
  fill: currentColor;
  d: path("M19.457 7H6.5A2.5 2.5 0 0 0 4 9.5v.903l12 6.462l3.464-1.866l.033.002h4.184l-7.206 3.88a1 1 0 0 1-.949 0L4 12.674v9.827A2.5 2.5 0 0 0 6.5 25h19a2.5 2.5 0 0 0 2.5-2.5V15h1.503q.258-.001.497-.05v7.55a4.5 4.5 0 0 1-4.5 4.5h-19A4.5 4.5 0 0 1 2 22.5v-13A4.5 4.5 0 0 1 6.5 5h13.959zm3.707-5.172c.553-1.104 2.12-1.104 2.672 0l5.002 9.992c.5 1-.222 2.18-1.336 2.18H19.498c-1.114 0-1.837-1.18-1.336-2.18zM24.5 11a.5.5 0 1 0 0 1a.5.5 0 0 0 0-1m0-7a.5.5 0 0 0-.5.5v5a.5.5 0 0 0 1 0v-5a.5.5 0 0 0-.5-.5");
}

</style>
