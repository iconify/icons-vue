<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8oss5bty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pen-size-5-outline-sharp" /></template>
<style>
.o8oss5bty {
  fill: currentColor;
  d: path("M5.48 16q0-1.038.741-1.779l8-8q.74-.74 1.779-.74t1.779.74t.74 1.779t-.74 1.779l-8 8q-.74.74-1.779.74t-1.779-.74T5.481 16");
}

</style>
